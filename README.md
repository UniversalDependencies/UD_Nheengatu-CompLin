# Summary

The UD_Nheengatu-CompLin is a treebank of [Nheengatu](https://glottolog.org/resource/languoid/id/nhen1239), also known, e.g., as Modern Tupi and *Língua Geral Amazônica*. It comprises sentences from diverse published sources, e.g., grammatical descriptions, fables, coursebooks, and dictionaries.


# Introduction

To our knowledge, this is the first treebank of Nheengatu. It is a work in progress. The initial release only contained a couple hundred sentences. This new release encompasses more than four times this number. We plan to continually expand the resource in the next months.

The treebank comprises sentences from diverse published sources freely available on the Internet, e.g., grammatical descriptions, fables, coursebooks, and dictionaries. The sentences were either extracted from PDF text files, transcribed from non-searchable (image-only) PDF files, or manually converted to orthography from phonetic transcriptions. Throughout the treebank, we use the spelling system of Navarro (2016), which only contains minor differences from Avila (2021)'s. The annotation was performed semi-automatically, i.e., we applied a Python program to the output of a morphological analyzer, manually revising each automatically annotated sentence.

The development of this treebank and related tools and resources is part of the research activities of the Research Group on Computation and Natural Language (*Computação e Linguagem Natural* — CompLin) at the Humanities Center of the Federal University of Ceará in Brazil. The main contributor to this effort is Leonel Figueiredo de Alencar, coordinator of the CompLin group. Additional annotators include Dominick Maia Alexandre. For more information, please visit the corresponding repository:

https://github.com/CompLin/nheengatu

So far, the treebank includes examples from Moore, Facundes, and Pires (1994), Casasnovas (2006), Cruz (2011), Comunidade de Terra Preta (2013), Navarro (2016), Alencar (2021), and Avila (2021) as well as from the New Testament (*Novo Testamento na língua Nyengatu*, 1973/2019).

# Acknowledgments

We are grateful to Eduardo de Almeida Navarro (University of São Paulo) for kindly allowing us to use examples and texts from his coursebook (Navarro 2016) in this project. Besides, the glossary of this coursebook was the first basis for the morphological analyzer.

We also acknowledge the use of Avila (2021)'s dictionary, from which numerous treebank sentences stem. This dictionary also provided invaluable lexical, grammatical, and semantic information for the further development of the morphological analyzer and related treebank annotation tools. We are much obliged to its author, Marcel Twardowsky Avila, for making the XML version of the dictionary available to us and clarifying questions about some entries.     

## License

Copyright of the treebank sentences and their translations belongs to their respective authors. This data is made available here solely to promote research, teaching, and learning of the Nheengatu language. Therefore, it shouldn't be used for any commercial purposes. For more information, see LICENSE.txt.

## References

* Alencar, Leonel Figueiredo de. (2021). Uma gramática computacional de um fragmento do nheengatu / A computational grammar for a fragment of Nheengatu. _Revista de Estudos da Linguagem, 29_(3), 1717-1777. doi:http://dx.doi.org/10.17851/2237-2083.29.3.1717-1777
* Avila, Marcel Twardowsky.(2021). *Proposta de dicionário nheengatu-português* [Doctoral dissertation, University of São Paulo]. doi:10.11606/T.8.2021.tde-10012022-201925
* Casasnovas, Afonso. (2016). *Noções de língua geral ou nheengatú: gramática, lendas e vocabulário* (2nd ed.). Editora da Universidade Federal do Amazonas; Faculdade Salesiana Dom Bosco.
* Comunidade de Terra Preta. (2013). *Fábulas de Terra Preta: Uma coletânea bilingüe*.
* Cruz, Aline da. (2011). *Fonologia e gramática do nheengatú: a língua falada pelos povos Baré, Warekena e Baniwa*. Netherlands National Graduate School of Linguistics.
* Moore, Denny, Facundes, Sidney, & Pires, Nádia. (1994). *Nheengatu (Língua Geral Amazônica), its History, and the Effects of Language Contact*. UC Berkeley: Department of Linguistics. Retrieved from https://escholarship.org/uc/item/7tb981s1
* Navarro, Eduardo de Almeida. (2016). *Curso de Língua Geral (nheengatu ou tupi moderno): a língua das origens da civilização amazônica* (2nd ed.). Centro Angel Rama da Faculdade de Filosofia, Letras e Ciências Humanas da Universidade de São Paulo.
* *Novo Testamento na língua Nyengatu* (2nd ed.). (2019). Missão Novas Tribos do Brasil. (Original work published 1973)


# Changelog

* 2022-11-15 v2.11
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.11
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: spoken bible fiction nonfiction grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: manual native
Relations: manual native
Contributors: de Alencar, Leonel Figueiredo
Contributing: elsewhere
Contact: leonel.de.alencar@ufc.br
===============================================================================
</pre>
