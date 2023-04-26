# Dark Magician Staff

## About

The model was built using [Blender](https://www.blender.org/), exported as a `.stl` file, imported into [PrusaSlicer](https://www.prusa3d.com/page/prusaslicer_424/), sliced and the result is saved as a `.gcode` file. This print was designed around it being printed on a Prusa Mini+ and Prusa i3 MK3S+.

> _**IMPORTANT:**_ It is never recommended to print from someone elses gcode files. Please use the STL files in your slicer of choice and generate the gcode on your own. Please let me know if you have any questions and thank you! Enjoy these prints!

## Print Volumes

| Version 1                      |  X, Y, Z (Prusa Mini+)   | X, Y, Z (Prusa i3 MK3S+) |
| -----------                    | -----------              | -----------              |
| STL                            | 180mm X 180mm X 180mm    | 250mm X 210mm X 210mm    |
| rod1.stl                       | Yes                      | Yes                      |
| rod2.stl                       | Yes                      | Yes                      |
| rod3.stl                       | Yes                      | Yes                      |
| rod4.stl                       | Yes                      | Yes                      |
| rod5.stl                       | Yes                      | Yes                      |
| rod6.stl                       | Yes                      | Yes                      |
| staff_footer1.stl              | No                       | Yes                      |
| staff_footer_bottom_left1.stl  | Not yet tested           | Not yet tested           |
| staff_footer_bottom_right1.stl | Not yet tested           | Not yet tested           |
| staff_sphere_bottom1.stl       | Not yet tested           | Not yet tested           |
| staff_sphere_top1.stl          | Not yet tested           | Not yet tested           |
| staff_tip1.stl                 | Not yet tested           | Not yet tested           |
| staff_tip2.stl                 | Not yet tested           | Not yet tested           |

> For staff_tip1 and staff_tip2 STL files you will need to chop them up in your slicer to fit on your bed. With the curvature or bend of these parts it may be difficult to have holes for wooden dowels. **If you need help with chopping these parts up, please create an issue in this repo and assign it to me. I will help you out as quickly as I can.** A glue I recommend is J-B Weld Plastic Bonder. 

## Images

## Contributing

- There is a good chance if you are here you have git installed. If not please install Git [here](https://git-scm.com/).

- Next you will need to install Git LFS as well. If you don't have that installed yet you can download it [here](https://git-lfs.com/).

- Clone the repo.

- Create an issue, filling in the title and comment section with details about what you will be working on and assign it to yourself.

- Create a branch after the issue number. The issue number is in the URL of the issue. If it's the first issue the URL will read something like /issues/1. You can create a branch running this in git bash of the cloned repo: 

        git checkout -b issues_1

- Once your changes are complete push your branch up and create a pull request. I will try to review your changes within two days of the creation of the PR. 

Currently I am using Blender 3.4.1. Check out these add ons that have helped me using Blender for creating 3D models for 3D printing:

- 3D View: MeasureIt
- Import-Export: STL Format
- Mesh: 3D-Print Toolbox

Please reach out to me if you have any questions and thank you!

## License

Creative Commons Zero v1.0 Universal [License](LICENSE)
