## SkEye Translations
This project hosts the translations for strings used in [SkEye][1].

  [1]: http://lavadip.com/1830_introducing_skeye.html

SkEye is primarily developed in English. Translations have been contributed by community.

## Credits
  * French translation by Germain Gagnerot

## License & Copyright
All translations are copyright Harshad RJ and are in the public domain. Anyone can use these
translations for any projects, commercial or non-commercial, closed-source or open-source.

When you create a translation, you will have to assign the copyright to Harshad RJ. I will add your
name to the credits (unless you request not to).

## What can be translated
Currently, only strings used in the User Interface can be translated. Translations for
astronomical object names is planned but not implemented yet.

## HowTo
If you know how Android handles Strings, then you can just follow the standard conventions.

If you are not familiar with Android String conventions, don't worry, it is easy to grasp. There is one XML
file for each localisation. Here localisation means a (country + language) pair.

For example, American English and UK English are two different localisations. Similarly, the French in France
would be different from the French in Canada.

However, if the country is not specified, then that translation is applied globally, irrespective of country.

Another handy rule is that, if the translation for a string doesn't exist, it falls back to the string specified
in the default XML file.

In the case of SkEye, we can initially focus only on non-country specific translations. Though if you want
to add country specific translations you are welcome.

TODO: Expand this further
