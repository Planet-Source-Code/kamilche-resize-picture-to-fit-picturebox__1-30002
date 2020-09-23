<div align="center">

## Resize Picture to Fit Picturebox


</div>

### Description

A one-liner that resizes a picture to fit the dimensions of a picturebox. No API calls.
 
### More Info
 
Picture1 autoredraw should be 'true'

Form and picturebox scalemode should be 'vbPixels'


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kamilche](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kamilche.md)
**Level**          |Beginner
**User Rating**    |4.9 (44 globes from 9 users)
**Compatibility**  |VB 6\.0
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__1-46.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kamilche-resize-picture-to-fit-picturebox__1-30002/archive/master.zip)





### Source Code

```
Picture1.Picture = LoadPicture(FileName)
Picture1.PaintPicture Picture1.Picture, 0, 0, Picture1.Width, Picture1.Height
```

