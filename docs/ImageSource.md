<!-- This file was autogenerated from ImageSource.tsx do not modify -->

```tsx
import { ImageSource } from '@rnmapbox/maps';

ImageSource
```
ImageSource is a content source that is used for a georeferenced raster image to be shown on the map.
The georeferenced image scales and rotates as the user zooms and rotates the map

## props

  
### id

```tsx
string
```
_required_
A string that uniquely identifies the source.


  
### existing

```tsx
boolean
```
The id refers to en existing source in the style. Does not create a new source.


  
### url

```tsx
number | string
```
An HTTP(S) URL, absolute file URL, or local file URL to the source image.
Gifs are currently not supported.


  
### coordinates

```tsx
tuple
```
The top left, top right, bottom right, and bottom left coordinates for the image.


  
### children

```tsx
React.ReactElement | React.ReactElement[]
```
FIX ME NO DESCRIPTION


  






