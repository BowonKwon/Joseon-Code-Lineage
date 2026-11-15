# 조선 법전 계보 · Lineage of the Joseon Codes

『경국대전』(1485)에서 『대전회통』(1865)까지, 조선 법전 밖에 쌓인 왕의 명령(수교)과 그것을 모은 중간 편찬물을 원문 데이터로 세는 역사 사이트입니다. 편찬물이 조문마다 밝힌 출처 표지를 따라가고, 표지 판독·날짜·조문 분절을 따로 확인한 결과를 함께 싣습니다.

A history site that counts, in open source-text data, the royal instructions (sugyo) that piled up outside the codes of Joseon between the *Gyeongguk daejeon* (1485) and the *Daejeon hoetong* (1865), and the intermediate compilations that gathered them. It follows the source marks the compilations put on their provisions and reports separate checks of mark reading, dates and provision boundaries.

- 사이트 · Site: https://bowonkwon.github.io/Joseon-Code-Lineage/

## 내용 · Contents (0.9)

| 장 · Chapter | 시기 · Period | 0.9 |
|---|---|---|
| 1. 경제육전에서 경국대전으로 · From the *Gyeongje yukjeon* to the *Gyeongguk daejeon* | 1397–1485 | 1.0에서 · in 1.0 |
| 2. 법전 밖에 쌓인 수교 — 속록과 후속록 · Royal instructions outside the code: the *Songnok* and *Husongnok* | 1485–1543 | ○ |
| 3. 수교의 시대 — 수교집록에서 증보전록통고까지 · The age of royal instructions: from the *Sugyo jimnok* to the *Jeungbo jeollok tonggo* | 1543–1738 | ○ |
| 4. 속대전 · The *Sok daejeon* | 1740–1746 | 1.0에서 · in 1.0 |
| 5. 1786년의 단면 — 『전율통보』가 밝힌 출처 · A cross-section of 1786: the sources named by the *Jeonyul tongbo* | 1786 | ○ |
| 6. 대전회통 · The *Daejeon hoetong* | 1786–1865 | 1.0에서 · in 1.0 |
| 7. 법전 계보의 끝 · The end of the line | 1865– | 1.0에서 · in 1.0 |

실록 속 법전, 신뢰도, 방법, 데이터 면이 따로 있습니다. 1·4·6·7장은 『경국대전』·『속대전』·『대전통편』·『대전회통』 본문이 필요해 1.0으로 미뤘습니다. 이 네 법전은 아래 개방 데이터에 들어 있지 않습니다.

Separate pages cover the codes in the Veritable Records, reliability, method and data. Chapters 1, 4, 6 and 7 need the text of the *Gyeongguk daejeon*, *Sok daejeon*, *Daejeon tongpyeon* and *Daejeon hoetong*, which the open data below does not contain, and are left for 1.0.

## 데이터 · Data

`data/` 의 CSV(UTF-8)는 이 사이트가 원문 데이터에서 직접 센 값입니다. 원천은 둘입니다.

- 국사편찬위원회 「조선시대 법령자료」 개방 데이터(공공데이터포털 15060103) — 중간 편찬물 일곱(『대전속록』·『대전후속록』·『수교집록』·『전록통고』·『신보수교집록』·『증보전록통고』·『전율통보』)의 XML.
- 국사편찬위원회 「조선왕조실록 정보」 개방 데이터(공공데이터포털 15053647, 고종·순종실록은 15053646).

The CSV files in `data/` (UTF-8) hold values counted for this site from two sources: the National Institute of Korean History's open data "Joseon legal materials" (data.go.kr 15060103), which holds the XML of the seven intermediate compilations, and its open data "Veritable Records of the Joseon Dynasty" (data.go.kr 15053647; records of Gojong and Sunjong, 15053646).

**싣는 것과 싣지 않는 것 · What is and is not republished**

- 법령자료 XML에서는 집계, 노드·구간 ID, 출처 표지, 한자 수, 날짜 문자열, 규장각 원문 면 번호, 짧은 인용만 싣습니다. 본문 전문은 싣지 않습니다.
- 고종·순종실록(공공누리 제4유형)은 법전 이름이 나오는 기사를 세기만 했고 인용하지 않습니다.
- 규장각한국학연구원 원문검색서비스의 면 이미지는 열람만 했고 싣지 않습니다. 구간 표의 면 번호로 원문 면을 찾아갈 수 있습니다.

- From the legal-materials XML, only counts, node and segment IDs, source marks, character counts, dated strings, Kyujanggak page numbers and short quotations are republished. The full text is not.
- The records of Gojong and Sunjong (KOGL Type 4) were only counted for articles naming a code; nothing from them is quoted.
- Page images from the Kyujanggak Institute's original-text service were viewed, not republished. The page numbers in the segment table lead to them.

## 하지 않는 것 · Scope

조선 법의 복잡도를 하나로 재는 종합 지수를 만들지 않고, 단위가 다른 숫자(조목·조문·날짜 문자열·기사)를 한 줄로 잇지 않으며, 인과를 말하지 않습니다. 출처 표지는 편찬자가 밝힌 출처이지 조문이 처음 만들어진 해가 아닙니다.

The site builds no composite index of legal complexity, does not splice counts in different units (headings, provisions, dated strings, articles) into one line, and makes no causal claims. A source mark records the source the compilers named, not the year a provision was first made.

## 판 · Versions

- **0.9.1** (2026-11-16) — 그래프 설명을 보강했습니다. 책 이름에 한글을 함께 적고, 축 이름·단위와 그래프마다 읽는 법을 더했습니다. 『신보수교집록』의 연도는 근거를 확인하지 못해 데이터 파일에서 비웠습니다(종전 1743). 그 밖의 수치는 바뀌지 않았습니다. · Chart explanations filled in: Hangul readings beside the book names, named axes with units, and a note on how to read each chart. The year of the Sinbo sugyo jimnok could not be confirmed and is now empty in the data file (it was 1743). No other value changed.
- **0.9** (2026-11) — 중간 편찬물 일곱, 2·3·5장, 실록 속 법전, 신뢰도. · Seven intermediate compilations; Chapters 2, 3 and 5; Codes in the Sillok; Reliability.

## 라이선스 · License

[LICENSE.md](LICENSE.md)
