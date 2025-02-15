# Chain Plate Wheels ISO606 simplex Simplex 1" ½ x 1" from z 8 to z 30

This folder contains the 3D model of the plate wheels for ISO 606 chains simplex 1" ½ x ¾" with number of teeth ranging from z=8 to z=30.

![Image](screenshot.png "Plate Wheel Simplex")

The model is parametric and the values are contained in the spreadsheet `Data`.

The parameters refer to the plate wheel dimensions as in the drawing below:

![Drawing](drawing.png "Drawing")

### Table of dimensions in millimeters:

P (Pitch)|Wc (Chain width)|Dr (Roller diameter)|Tr (Tooth radius)|Rw (Radius width)|Wt (Tooth width)|z (Number of teeth)|De (External Diameter)|Dp (Pitch diameter)|D (Hole diameter)|H (Total height)
---|---|---|---|---|---|---|---|---|---|---
38,1|25,4|25,4|38|4|24,1|8|115|99,55|25|24,1
38,1|25,4|25,4|38|4|24,1|9|126,4|111,4|25|24,1
38,1|25,4|25,4|38|4|24,1|10|138|123,29|25|24,1
38,1|25,4|25,4|38|4|24,1|11|150|135,21|25|24,1
38,1|25,4|25,4|38|4|24,1|12|162|147,22|25|24,1
38,1|25,4|25,4|38|4|24,1|13|174,2|159,18|25|24,1
38,1|25,4|25,4|38|4|24,1|14|186,2|171,22|25|24,1
38,1|25,4|25,4|38|4|24,1|15|198,2|183,26|25|24,1
38,1|25,4|25,4|38|4|24,1|16|210,3|195,3|25|24,1
38,1|25,4|25,4|38|4|24,1|17|222,3|207,34|25|24,1
38,1|25,4|25,4|38|4|24,1|18|234,3|219,42|25|24,1
38,1|25,4|25,4|38|4|24,1|19|246,5|231,49|25|24,1
38,1|25,4|25,4|38|4|24,1|20|258,6|243,57|25|24,1
38,1|25,4|25,4|38|4|24,1|21|270,6|255,65|30|24,1
38,1|25,4|25,4|38|4|24,1|22|282,7|267,73|30|24,1
38,1|25,4|25,4|38|4|24,1|23|294,8|279,8|30|24,1
38,1|25,4|25,4|38|4|24,1|24|306,8|291,88|30|24,1
38,1|25,4|25,4|38|4|24,1|25|319|304|30|24,1
38,1|25,4|25,4|38|4|24,1|26|331|316,08|30|24,1
38,1|25,4|25,4|38|4|24,1|27|343,2|328,19|30|24,1
38,1|25,4|25,4|38|4|24,1|28|355,2|340,27|30|24,1
38,1|25,4|25,4|38|4|24,1|29|367,3|352,38|30|24,1
38,1|25,4|25,4|38|4|24,1|30|379,5|364,5|40|24,1

The 3D model configuration of each plate wheel can be dynamically retrieved using a preset `Configuration table`.
The file name of the 3D model containing the `Configuration table` is **`Plate Wheel simplex 1 ½ x 1.FCStd`**.

To obtain the 3D model of the desidered plate wheel, click the spreadsheet `Data` in the Tree View and then select the `Teeth Number` in the property editor. If nothing changes try to `Refresh` the model.

See the following image for details

![Drawing](configuration.png "Configuration")

### Notes for developers
If you add a row in the `Configuration table` of the `Data` spreadsheet, then add that row in the above table of this `README.md` file, without the first cell.
