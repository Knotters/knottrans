# Contribution

To translate in any language, the language specific `django.po` file is present at `locale/<language-code>/LC_MESSAGES/django.po`.
The `<language-code>` is the code for specific language. (like `hi` for Hindi)

The format of translation is

```po
msgid "Message ID"
msgstr "Message value"
msgid ""
"Some Message ID with variable %(NAME)s"
msgstr ""
"Some Message value with %(NAME)s as variable"
```

Following is an example for `hi` language code

```po
msgid "You're welcome"
msgstr "आपका स्वागत है"
msgid ""
"Thank you %(USERNAME)s for your "
"contribution to the translation."
msgstr ""
"अनुवाद में अपने योगदान के लिए %(USERNAME)s "
"का धन्यवाद।"
```

Keep the translations gender neutral if applicable, and use respectable tone of translation in your language.
Do not use foul or explicit terms in translations.
