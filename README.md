# PrepAdmisionTest
Useful to replicate the admission process, for the postgraduate entrance exam.


**The instructions are as follows:**

1. Fork this repository into your own account.

2. Clone the repository to your computer so you have local access. For the remainder of the problem, you can use the language of your preference.

3. At the address [https://www.gob.mx/salud/documentos/datos-abiertos-152127](https://www.gob.mx/salud/documentos/datos-abiertos-152127), you can consult the file found in the Database section with the data on the evolution of COVID in Mexico.

4. Create a program that does the following:
   - Download the COVID data file & the data dictionary.
   - Add the .csv data files to the .gitignore.
   - Generate a figure with 3 graphs, showing the weekly lethality of COVID throughout the pandemic for Mexico, the state of Sonora, and the municipality of Hermosillo (in Sonora). You will likely need to consult the data dictionary, which is downloaded as a separate file from the same site. Save it in a file named figure.png.
   - Generate a table with the number of admissions, number of deaths, and the lethality rate, but now calculated by age group (you are free to select the ranges, but one could be from 0 to 18 years, 18 to 30 years, 30 to 60 years, and over 60 years). Save it in the file tabla.csv.zip.
   - Modify the README.org file to explain what is done in the repository.

5. Make a commit and update the repository.

6. Submit a link to your repository in your exam.

Lethality is calculated as the accumulated number of patients admitted relative to the number of patients who ultimately died. In this case, the accumulations (for the figure) are taken on a weekly basis and only with the date of admission to the hospital system. These are data only for patients who were admitted to hospitalization. Lethality gives us an idea of the aggressiveness of the virus, without reflecting numbers globally (for that, the mortality rate per 100,000 inhabitants is used). Keep in mind that the only way to know if a patient died is because they have a date of death (fortunately, the vast majority do not have a date of death).

**Evaluation Criteria:**
- The quality of the code written.
- Documentation of the code and the data.
- The solution to create the requested tables and graphs.
- The quality of the graphs.

Good luck!
