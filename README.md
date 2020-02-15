## Extract from chess-mobile project
#### by Stanisław Kabaciński, 2017

To see how a PGN file is loaded into memory, please refer to TestPgnRead class in "test" package.

Change history:
- 2018/09/01 - added class test.TestPgnRead (mszelag)
- 2018/12/16 - added comments in test.TestPgnRead class (mszelag)
- 2018/12/16 - package `chess.mobile.chessgame` renamed to `chess.parser` (mszelag)
- 2020/02/15 - add notifying observers of `ObservableChessBoard` on `makeMove` with coordinates passed (wkups)
- 2020/02/15 - migrate project to gradle (wkups)
