## **[ XMLparser ]**
**Simple parser for modifying all xml files of a certain type inside a folder.
This parser is used to modify the size of hangars in the game [Stormworks](https://store.steampowered.com/app/573090/Stormworks_Build_and_Rescue/).**

---

### **[ WARNING! ]**
This parser can create additional file and directory (```Roaming\xml_parser\xml_parser.cfg```).
Also parser can modificate all ```.xml``` files in a folder.

---

### **[ Options ]**
The first input uses for entering path of tiles folder. (```...\Stormworks\rom\data\tiles```)
(The parser remembers the entered path by creating a file ```xml_parser.cfg``` in the ```Roaming\xml_parser\``` directory
and saving the entered path there. Then the next time you start the path input field will be automatically filled in with the contents of the file.)

The second input uses for entering a size of a hangar. (400 for example)

The third input can change the pattern for searching ```.xml``` files. (default str. value is ``` '*island*.xml' ```)

---

### **[ Exceptions ]**
*```"Please enter correct path to tiles folder!"```* | A non-existent path to the tiles folder was entered. The error is related to 1 input field.

*```"Wrong path or incorrect additional params!"```* | The folder exists but no ```.xml``` files were found in it or they do not match the additional params search pattern. The error is related to 1 or 3 input field.

*```"Broken files"```* | Error when changing ```.xml``` file, the chance of occurrence is minimal. The error is related to 1 input field.

---
