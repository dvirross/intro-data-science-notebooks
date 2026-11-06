# Introduction to Data Science: course notebooks

Jupyter notebooks that accompany the lessons of the Introduction to Data Science course on [dvirross.com](https://dvirross.com/courses/intro-data-science). Each notebook is written by Dvir Ross and runs top to bottom in Google Colab without an account key.

## The minimum Python for working with SQLite

Lesson: [The minimum Python for working with SQLite](https://dvirross.com/courses/intro-data-science/python-sqlite-minimum). The notebooks are generated from the lesson page, so the tasks have the same numbers, wording and expected output on the page and in the notebook.

| Language | Tasks | Solutions |
|---|---|---|
| English | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare.ipynb) | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare-solutions.ipynb) |
| Hebrew | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare.he.ipynb) | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare-solutions.he.ipynb) |

Files: `sql-python-sqlite-bikeshare.ipynb`, `sql-python-sqlite-bikeshare-solutions.ipynb` and the same two with `.he` before `.ipynb` for Hebrew.

## Tables as Python objects: a first look at Pony ORM

Lessons: [Tables as Python Objects: A First Look at Pony ORM](https://dvirross.com/courses/intro-data-science/python-orm-pony) (part 1, tasks 1 to 7) and [Pony ORM Relations: A Table That Points to Another Table](https://dvirross.com/courses/intro-data-science/python-orm-pony-relations) (part 2, tasks 8 to 11). One notebook covers both lessons, and a heading marks where each part starts. The first cell installs Pony (`pip install pony`) if needed, and a setup cell downloads one small CSV file from dvirross.com. The notebooks are generated from the lesson pages, so the tasks have the same numbers and wording on the pages and in the notebook.

| Language | Tasks | Solutions |
|---|---|---|
| English | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.ipynb) | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.ipynb) |
| Hebrew | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.he.ipynb) | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.he.ipynb) |

Files: `orm-pony-bikeshare-worldbank.ipynb`, `orm-pony-bikeshare-worldbank-solutions.ipynb` and the same two with `.he` before `.ipynb` for Hebrew.

Data: the bike-share days above and an extract of the World Bank World Development Indicators (CC BY 4.0).

## Data

The notebooks download the course database from the public site: `https://dvirross.com/materials/courses/intro-data-science/sql-practice.sqlite`. The table `daily_ridership` holds 731 real days (2011 and 2012) of the Capital Bikeshare system, from the UCI Bike Sharing dataset (Fanaee-T and Gama, 2013), licensed CC BY 4.0.

## Rights

The notebooks are by Dvir Ross, all rights reserved unless a license file says otherwise. The data keep their own license (CC BY 4.0).

---

# מבוא למדעי הנתונים: מחברות הקורס

מחברות Jupyter שמלוות את השיעורים של הקורס מבוא למדעי הנתונים באתר [dvirross.com](https://dvirross.com/he/courses/intro-data-science). כל מחברת נכתבה על ידי דביר רוס, ורצה מההתחלה ועד הסוף ב-Google Colab בלי מפתח.

## Python מינימלי לעבודה עם SQLite

שיעור: [Python מינימלי לעבודה עם SQLite](https://dvirross.com/he/courses/intro-data-science/python-sqlite-minimum). המחברות נגזרות מדף השיעור, ולכן למשימות אותו מספר, ניסוח ופלט צפוי בדף ובמחברת.

| שפה | משימות | פתרונות |
|---|---|---|
| עברית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare.he.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare-solutions.he.ipynb) |
| אנגלית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/sql-python-sqlite-bikeshare-solutions.ipynb) |

## טבלאות כאובייקטים ב-Python: היכרות עם Pony ORM

שיעורים: [טבלאות כאובייקטים ב-Python: היכרות ראשונה עם Pony ORM](https://dvirross.com/he/courses/intro-data-science/python-orm-pony) (חלק 1, משימות 1 עד 7) ו[Pony ORM: טבלה שמצביעה על טבלה אחרת](https://dvirross.com/he/courses/intro-data-science/python-orm-pony-relations) (חלק 2, משימות 8 עד 11). מחברת אחת מכסה את שני השיעורים, וכותרת מסמנת איפה כל חלק מתחיל. התא הראשון מתקין את Pony אם צריך, ותא ההכנה מוריד קובץ CSV קטן מהאתר. המחברות נגזרות מדפי השיעורים, ולכן למשימות אותו מספר וניסוח בדפים ובמחברת.

| שפה | משימות | פתרונות |
|---|---|---|
| עברית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.he.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.he.ipynb) |
| אנגלית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.ipynb) |
