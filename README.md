# camunda-optimize-translations

This project provides translations for Camunda Optimize. While the English and German language files will be updated by the Optimize team with each release, other language files will not be officially supported by Camunda. We encourage others to create PRs to keep these updated and aligned with the latest language files.

Please read more about Optimize localization here: https://docs.camunda.io/docs/next/self-managed/optimize-deployment/configuration/localization/

> [!NOTE]
> If any translation key is missing in the translation file, it will cause Optimize to crash when used.


### Contributing

Everybody is welcome to contribute! You can help by sending us a pull request with your translation.
Please keep the naming conventions:

- localisation file `X.json`

where `X` is the two letter language abbreviation.
Please also put your files into proper version folder.

> [!NOTE]
> For versions of Optimize <= 3.13, the `whatsnew_X.md` file must also be included

# History

## Add chinese-simplized translation for 3.13

1. zh.json in folder .\3.13\localisation
2. whatsnew_zh.md in folder .\3.13\whats-new
