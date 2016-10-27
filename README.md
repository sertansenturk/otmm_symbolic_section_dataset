otmm_symbolic_section_dataset
=============================
The section test dataset of music scores of Ottoman-Turkish makam music

This repository contains the audio section annotations and the scores used in the paper:

> Şentürk, S., & Serra X. (2016). A method for structural analysis of Ottoman-Turkish makam music scores. In Proceedings of 6th International Workshop on Folk Music Analysis, (pp. 39–46)., Dublin, Ireland.

Please cite the publication above in any work using this dataset.

The repository contains a test dataset of the SymbTr scores of 23 vocal compositions in
the şarkı form and 42 instrumental compositions in peşrev
and sazsemaisi forms in the txt and pdf format. The scores are selected from the [release version 2.4.2](https://github.com/MTG/SymbTr/tree/v2.4.2) and the section annotations done by the first author of the paper. In the sections folder, the annotated sections for each score are stored in a tsv file, which has the same name as the SymbTr-name (makam--form--usul--name--composer) of the annotated score. The fields are:

```
  start_note:         The starting note index in the SymbTr-txt score
  end_note:           The ending note index in the SymbTr-txt score
  name:               The basic semantic name of the section. Right now, it is the name 
                      (TESLİM, ARANAĞME...) annotated in the score for instumental sections or 
                      "VOCAL_SECTION" for vocal sections.	
  melodic_structure:  Melodic semiotic label
  lyric_structure:    Lyrical semiotic label	
  lyrics:             Lyrics of the section
  slug:               The processed version of "name" field with the Turkish characters and 
                      special characters handled.
```

For the details of the dataset, please refer to the paper. For any further information please contact the authors.
