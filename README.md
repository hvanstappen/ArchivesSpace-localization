# ArchivesSpace-localization
Dutch localization files for the ArchivesSpace application v. 3.0 - but should work in older versions too (not tested)
These are drafts, replacing the en.yml files (dutch as an additional language should be configured, is TODO)
No localization for the PUI, sorry :(

3 files
1. en_YYYYMMDD.yml: 
- rename to en.yml
- move to /locales folder

2. enums-en_YYYYMMDD.yml: 
- rename to en.yml
- move to /locales/enums folder

3.wars-en_YYYYMMDD.yml:
- rename to en.yml
- move to WEB.INF/config/locales  in wars/frontend.war (you'll first need to extract and then recompress the .war file)

see also
- https://archivesspace.org/
- https://github.com/archivesspace/archivesspace/blob/master/public/config/locales/en.yml
- https://archivesspace.github.io/tech-docs/customization/locales.html
