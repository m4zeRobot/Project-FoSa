# Project-FoSa
Recreating the source files to the equation cheat-sheets from FLURUS - the student council of the aerospace degree program at the University of Stuttgart, Germany.

## Why does this project exist?
From finally vectorizing all the images to enable sharp quality printouts to letting people fix obvious mistakes on their own, this project arose with the goal of improvement in mind.
If you want to contribute, just text me for repo access!

### Advantages
- The whitespace of each document has been optimized to save the most precious thing when creating an Equation Cheat-Sheet: space.
- Each graphic has been re-created as a vector graphic, letting you a) fix possible mistakes and b) making it crisp after printing, all while c) colorizing each image for easier recognition.
- Useful notes have been added to each document, from CAS commands over simple page numbers to equation numbers, all in accordance with the respective lecture.
- Giving the power to fix mistakes back to everyone!
- Since the original documents are all in German, this project enables easy translation to other languages.

## How the sheets are built
Each sheet consists of a hard division into so called "Tiles", and a soft sub-division of these tiles, into either columns of a `tabularx` environment or multiple `minipage` environments.
This makes the code look a bit messy here and there, but the results should always compile without any warnings.
The hard division is setting a clear structure to work within, while any form of soft sub-division allows for more flexibility.

<hr/>

## Some more things on the used nomenclature:
- **Indexes** are generally written upright, since any italic letter is supposed to refer to a variable. This does of course not apply to indexes that are variables themselves, e.g. counters like *i*, *n* etc.
- **Key Parameters** (such as the Mach or Laval numbers) are also written upright, even though they are technically variable per equation - this is just my personal preference.
- **Multiplications** are generally shortened by simply using a half-space (`\,`) in between the factors, instead of the central dot (`\cdot`) as you may know it. This is meant to save space and avoid confusingly long equations.