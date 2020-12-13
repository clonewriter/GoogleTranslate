# Google Translate


## Installation:
```
composer require ammarfaizi2/googletranslate
```


## Usage :
```php
<?php
require "src/GoogleTranslate.php";
// require "vendor/autoload.php"; // when using composer

use GoogleTranslate\GoogleTranslate;

// Translate from Indonesia to English.
$text = "Apa kabar?";
$from = "id"; // Indonesia
$to   = "en"; // English

$st = new GoogleTranslate($text, $from, $to);
$result = $st->exec();

echo $result; // How are you?
```


Available Languages:
| Code        | Description |
| ----------- | ----------- |
 | en | English |
 | ja | Japanese |
 | id | Indonesian |
 | af | Afrikaans |
 | sq | Albanian |
 | am | Amharic |
 | ar | Arabic |
 | hy | Armenian |
 | az | Azerbaijani |
 | eu | Basque |
 | be | Belarusian |
 | bn | Bengali |
 | bs | Bosnian |
 | bg | Bulgarian |
 | ca | Catalan |
 | ce | Cebuano |
 | ny | Chichewa |
 | zh | Chinese |
 | co | Corsican |
 | hr | Croatian |
 | cs | Czech |
 | da | Danish |
 | nl | Dutch |
 | en | English |
 | eo | Esperanto |
 | et | Estonian |
 | tl | Filipino |
 | fi | Finnish |
 | fr | French |
 | fy | Frisian |
 | gl | Galician |
 | ka | Georgian |
 | de | German |
 | el | Greek |
 | gu | Gujarati |
 | ht | Haitian Creole |
 | ha | Hausa |
 | ha | Hawaiian |
 | iw | Hebrew |
 | hi | Hindi |
 | hm | Hmong |
 | hu | Hungarian |
 | is | Icelandic |
 | ig | Igbo |
 | id | Indonesian |
 | ga | Irish |
 | it | Italian |
 | ja | Japanese |
 | jw | Javanese |
 | kn | Kannada |
 | kk | Kazakh |
 | km | Khmer |
 | rw | Kinyarwanda |
 | ko | Korean |
 | ku | Kurdish (Kurmanji) |
 | ky | Kyrgyz |
 | lo | Lao |
 | la | Latin |
 | lv | Latvian |
 | lt | Lithuanian |
 | lb | Luxembourgish |
 | mk | Macedonian |
 | mg | Malagasy |
 | ms | Malay |
 | ml | Malayalam |
 | mt | Maltese |
 | mi | Maori |
 | mr | Marathi |
 | mn | Mongolian |
 | my | Myanmar (Burmese) |
 | ne | Nepali |
 | no | Norwegian |
 | or | Odia (Oriya) |
 | ps | Pashto |
 | fa | Persian |
 | pl | Polish |
 | pt | Portuguese |
 | pa | Punjabi |
 | ro | Romanian |
 | ru | Russian |
 | sm | Samoan |
 | gd | Scots Gaelic |
 | sr | Serbian |
 | st | Sesotho |
 | sn | Shona |
 | sd | Sindhi |
 | si | Sinhala |
 | sk | Slovak |
 | sl | Slovenian |
 | so | Somali |
 | es | Spanish |
 | su | Sundanese |
 | sw | Swahili |
 | sv | Swedish |
 | tg | Tajik |
 | ta | Tamil |
 | tt | Tatar |
 | te | Telugu |
 | th | Thai |
 | tr | Turkish |
 | tk | Turkmen |
 | uk | Ukrainian |
 | ur | Urdu |
 | ug | Uyghur |
 | uz | Uzbek |
 | vi | Vietnamese |
 | cy | Welsh |
 | xh | Xhosa |
 | yi | Yiddish |
 | yo | Yoruba |
 | zu | Zulu |
