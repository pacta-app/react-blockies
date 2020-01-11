# React Blockies

This is a fork of [cssivision/qrcode-react](https://github.com/cssivision/qrcode-react), which a simple port of [alexvandesande/blockies](https://github.com/alexvandesande/blockies) to a react component. The original has been forked with the only intention to remove hard coded style and attributes. The stiling should be done with selectors in css files and must not be implemented hard coded.

# Example:

```javascript
import Blockies from 'react-blockies';

export const myBlockies = () => (
  <Blockies
    seed="Jeremy" {/* the only required prop; determines how the image is generated */}
    size={10} {/* number of squares wide/tall the image will be; default = 15 */}
    scale={3} {/* width/height of each square in pixels; default = 4 */}
    color="#dfe" {/* normal color; random by default */}
    bgColor="#ffe" {/* background color; random by default */}
    spotColor="#abc" {/* color of the more notable features; random by default */}
    className="identicon" {/* optional class name for the canvas element; "identicon" by default */}
  />
)
```
