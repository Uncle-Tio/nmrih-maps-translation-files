# [NMRiH] Translation Files (for [dysphie/sm-map-translator](https://github.com/dysphie/sm-map-translator))

NMO and NMS maps translation files for multiple languages using **dysphie/sm-map-translator**. Including **Vanilla** and most popular **Custom Maps** With help from the community.

You can submit new translations or suggest corrections. [See how](#how-to-contribute).

#### Requeriments:
- [[NMRiH/ZPS] Map Translator](https://github.com/dysphie/sm-map-translator) made by [dysphie](https://github.com/dysphie).
- The player must have a language selected in the game properties (on Steam).

🔎 *If the chosen language is not translated, English will be used (as default).*

#### Installation:
1. Download `nmrih-map-translations.zip` most recent from [releases](https://github.com/Uncle-Tio/nmrih-maps-translation-files/releases) (WIP).
2. Unzip folder `_maps` and put in your Sourcemod Translations folder `nmrih\addons\sourcemod\translations`.

⚠️ *If you have already translated any of the maps included in this repository, they will be **lost** when overwriting.*


## How to contribute:

For a more **noob friendly** tutorial, click [here](#how-to-contribute) *(Working on it/WIP)*.

When making contributions, copy the English language line and paste below and change the ID code from `"en"` to one from [this list](#tabela-de-ids-e-status) to add new translations. 

💡 *Use the English line as a reference*

#### Example:
```cpp
	}
	"1cd18ac0632cae7b0cda0cf34208a767"
	{						  ↙️ Copy this entire line
		"en"		"Unlock the hospital doors."
		"pt"		"Destranque as portas do hospital."
		"pt_p"		"Destranque as portas do hospital."
	Make a new line and paste ↘️				
	   	"en"	        "Unlock the hospital doors."
    Change the ID🔺					🔺 Translate to the language you have chosen.
	}
```
#### Result:
```cpp
	}
	"1cd18ac0632cae7b0cda0cf34208a767"
	{
		"en"		"Unlock the hospital doors."
		"pt"		"Destranque as portas do hospital."
		"pt_p"		"Destranque as portas do hospital."
		"es"		"Spanish things translated..."
	}
```

### Notes

- You must escape quotes with a backslash (`\`) to prevent parsing errors.

	```cpp
	// Example 
		"es"		"Destroy \"Robert\" the puppet"
	```


# Language code table and status.

|ID Codes|			 Language		      |				Status		      |   NMO maps   |   NMS maps   |
|:------:|:--------------------------------------------------:|:---------------------------------------------:|:------------:|:------------:|
| **en** |	🇺🇸 English				      |	       ♻️ Base Language 			|     ✔️      |      ✔️      |
| **de** |	🇩🇪 German (Deutsch)			      |	       ❌ Not Started |  |  |
| **fr** |	🇫🇷 French (Français)			      |	       ❌ Not Started |  |  |
| **it** |	🇮🇹 Italian (Italiano)			      |        ❌ Not Started |  |  |
| **ko** |	🇰🇷 Korean (한국어)			    |	     ❌ Not Started |  |  |
| **es** |	🇪🇸 Spanish (Español)			       |        ❌ Not Started |  |  |
| **ch** |	🇨🇳 Chinese Simplified (简体中文)		    |	     ❌ Not Started |  |  |
| **zho**|	🇨🇳 Chinese Traditional (繁體中文)		    |	     📋 *needs a double check*		    | 📝 **In Progress** | ⏳ **Not Started** |
| **ru** |	🇷🇺 Russian (Русский)			        |	 ❌ Not Started |  |  |
| **jp** |	🇯🇵 Japanese (日本語)			      |	      📋 *needs a double check*		     | 📝 **In Progress** | ⏳ **Not Started** |
| **pt** |	🇧🇷 Brazilian Portuguese (Português BR) 	|	✔️ Ready to Use		| ✔️ **Completed** | 📝 **In Progress** |
|**pt_p**|	🇵🇹 Portuguese (Português)			 |	📋 *Usable (adaptation needed)*			| ✔️ **Completed** | 📝 **In Progress** |
| **pl** |	🇵🇱 Polish (Polski)				 |	❌ Not Started  			      |  |  |
| **fi** |	🇫🇮 Finnish (Suomi)				 |	❌ Not Started  			      |  |  |
| **sv** |	🇸🇪 Swedish (Svenska)				 |	❌ Not Started  			      |  |  |
| **hu** |	🇭🇺 Hungarian (Magyar)				 |	❌ Not Started  			      |  |  |
| **tr** |	🇹🇷 Turkish (Türkçe)				 |	❌ Not Started  			      |  |  |
| **el** |	🇬🇷 Greek (Ελληνικά)				 |	❌ Not Started  			      |  |  |
| **ua** |	🇺🇦 Ukrainian (Українська)			 |	❌ Not Started  			      |  |  |
