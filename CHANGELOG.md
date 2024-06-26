# CHANGELOG

## Next release

- Fixed: names and id boxes now aligned with their title (header)
- Fixed: do not set fboxsep globally
- Fixed: error with QCM metadata
- Fixed: error with the y metadata value of inline answer zones
- Class renamed to correctexam to avoid clashes
- Add possibility to set a number of boxes in withid option
- New env questionExamBlock
- Add caution about minted and fboxsep in README
- warnings fixed
- Fix withID option
- Use \section for "Exercice" titles


## v1.5.0

### Changed

- fixed: not able to use vspace in answerExamContent
- fixed: the provided example using answerExamContent was not good

### Added
- feat: the PDF metadata now contains exercise ID

##  v1.4.0


- new: new command 'answerExamContent'

## v1.3.0

### Changed

- fixed: json metadata must use double quotes
- fixed: json metadata must contain the pages
- fixed: \booltrue or \boolfalse must be prefixed with \global
- fixed: incorrect size metadata for all boxes

## v1.2.0

### Changed

- fixed: ID cells enlarged

## v1.1.0

### Changed

- change: QCM are not more double inner qcmExam
       environments. See the example to adapt your code
- fixed: bad numbering QCMs
- fixed: bad dimensions of boxes on multi-column
- fixed: student if boxes color changed to lightgray
- fixed: do not compile when defining a first command with a label
- fixed: better alignment of student IDs in the header

### Added

- feat: add metadata related to: the answer zones
     of questions; student ids



