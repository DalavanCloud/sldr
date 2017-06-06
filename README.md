SIL Locale Data repository (SLDR)
------------------------------------

SIL has created its own repository of selected locale data. It serves two purposes; to gather information for publication on ScriptSource, and to gather information for submission to the Common Locale Data Repository (http://cldr.unicode.org/), a project to provide locale data for use in multilingual computer applications. The CLDR website is hosted by the Unicode Consortium. 

SIL International receives the data from users of the ScriptSource website and from other linguistic contacts.  We are particularly interested in submissions of Character List data, which enables ScriptSource to cross-reference writing systems with the characters they use.  For people who wish to add a language to the CLDR, we can store the CLDR minimal data set for that language in our repository.  This consists of the following fields:

Language Name

Script Name

Main Exemplar - the minimum set of alphabetic characters required for this writing system

Auxiliary Exemplar - characters which are used in this writing system for writing loan words only

Index Exemplar - the 'shortcut' letters for jumping to sections of a sorted, indexed list (such as a telephone directory)

Punctuation Exemplar - punctuation symbols required by the writing system

Orientation - direction of writing

Plural Rules - the number of plural forms which are needed to write any given noun

Default Script - the primary script used for writing the language (may be different from the Script Name field)

Default Region - the primary country where the language is spoken

Other Countries where spoken - other countries where the language is spoken

If the minimal data set is received for a language then it will be submitted as a "seed locale" to the CLDR. It is then possible for this "seed locale" to be developed into a full locale containing a broader set of data, at which point it will be published in the next release of the CLDR. In the case that only a subset of the minimal data listed above is received, it will be published on ScriptSource, but will not be submitted to the CLDR until their minimal requirements have been met.

If you are knowledgeable about a particular writing system and would like to submit information about it, we would welcome your submissions. Please take a look at Contributing to ScriptSource and the CLDR (http://scriptsource.org/entry/lr63742duf) for more details.

## LDML Editor

The [LDML Editor](http://scripts.sil.org/pub/ldmledit/#/loadnsave) is a small web application that allows a user to generate an LDML file without knowing the details of the syntax or the need to type a lot of XML.

The source code is located here: [https://github.com/silnrsi/sldr/tree/master/editor](https://github.com/silnrsi/sldr/tree/master/editor)

