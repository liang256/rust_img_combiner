# rust_img_combiner
A CLI tool to combine 2 input images into one.

This project is created following this [tutorial](https://youtu.be/MsocPEZBd-M)

### Uasge
```
$ cargo run -- [path/of/first/image] [path/of/second/image] [/path/of/output/image]
```
Note: 
- the formats of imput images must be the same, or it will panic.
- better to pick smaller images (less than 512*512) or it will take a while to combine.

### Examples of result
image 1:
<img src="https://images.unsplash.com/photo-1649812293699-0026834302ff?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1374&q=80" alt="forest" style="width:100%">

image 2:
<img src="https://images.unsplash.com/photo-1649825080587-cb51ca993e05?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80" alt="forest" style="width:100%">

output:
![output](https://user-images.githubusercontent.com/23650308/163326158-7009e9af-ec54-4f16-9ad5-83c672c67bc2.jpg)
