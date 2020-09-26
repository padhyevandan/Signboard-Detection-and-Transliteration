# Signboard-Detection-and-Transliteration

## Phases

### Signboard Detection
Extracts region of interest from the image i.e. the area containing some text.
Also detects the language of the text which is required in further phases.

### Text Recognition
Text from the region of interest is extracted obtained in previous step.
Language information can be used to select the corresponding model and character set.
Hindi word is extracted using Hindi character set and corresponding model.

### Transliteration
Hindi language text is transliterated to English.
