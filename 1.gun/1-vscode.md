# Kod Editör Kurulumu

# Visual Studio Code

Microsoft tarafından geliştirilen açık kaynaklı bir idedir.

* VsCode Sürümü (https://code.visualstudio.com/)
* Telemetry Olmayan Sürüm (https://vscodium.com/)



</br>

#### Kullanılacak Eklentiler;

| Eklenti Adı             | Kullanım Amacı                           
|-------------------------|------------------------------------------
|Python                   |Linter, Debug, Code Formatting            
|Bracket Pair Colorizer 2 |Parantez ve süslü parantezleri ayırt etme.
|Indent-rainbow           |Tabları renklendirir                      
|Visual Studio IntelliCode|Yapay zekalı asistan
|Pylance                  |Python yardimci kod tamamlayici          
|One Dark Pro             |Tema (opsiyonel)
|Vscode-icons             |Guzel iconlar (opsiyonel)         


#### Diğer Eklentiler
https://marketplace.visualstudio.com/VSCode

</br>

#### Diger Ayarlar
Settings > Open Settings.json

```json
"python.formatting.provider": "black",
    "[python]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
    "python.linting.pylintEnabled": false,
```

</br>

Settings.json
```json
{
    "workbench.startupEditor": "newUntitledFile",
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "workbench.iconTheme": "vscode-icons",
    "workbench.colorTheme": "One Dark Pro",
    "python.languageServer": "Pylance",

    //Custom Ayarlar
    "python.formatting.provider": "black",
    "[python]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
    "python.linting.pylintEnabled": false,
}
```