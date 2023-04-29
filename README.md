# domil-store README

Domil Store

## Features

Prepublish, remove cache, remove dist, paste dist

## How Setup

0. Press CTRL+SHIFT+X on VScode to see plugins tab. After that you need to click on more action (...) and click on Install from VSIX. Then open VSIX file.

1. You need to make ".store.json" on root of ba...-desktop. After that you need to set gsm project path. example:
   {
   "storePath": "D:\\Ba...-Project\\ba....-gsm",
   "prestaPath": "C:\\xampp\\htdocs\\ba...."
   }

Don't forget to replace single slash with double slash.

"storePath" => The ba...-gsm path

"prestaPath" => The perstashop path

2. Add ".store.json" to .gitignore

3. Now Press ctrl+shift+p : write "Copy Store". This command is for prepublish and move dist file to node_modules

4. Also You can Press ctrl+shift+p : write "Copy Prestashop". This command will build and move files to Prestashop. it's also update the version.

**Enjoy!**
