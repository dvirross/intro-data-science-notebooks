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

Lessons: [Tables as Python Objects: A First Look at Pony ORM](https://dvirross.com/courses/intro-data-science/python-orm-pony) (part 1, tasks 1 to 8) and [Pony ORM Relations: A Table That Points to Another Table](https://dvirross.com/courses/intro-data-science/python-orm-pony-relations) (part 2, tasks 9 to 13). One notebook covers both lessons, and a heading marks where each part starts. The first cell installs Pony (`pip install pony`) if needed, and a setup cell downloads one small CSV file from dvirross.com. The notebooks are generated from the lesson pages, so the tasks have the same numbers and wording on the pages and in the notebook.

| Language | Tasks | Solutions |
|---|---|---|
| English | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.ipynb) | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.ipynb) |
| Hebrew | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.he.ipynb) | [Open in Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.he.ipynb) |

Files: `orm-pony-bikeshare-worldbank.ipynb`, `orm-pony-bikeshare-worldbank-solutions.ipynb` and the same two with `.he` before `.ipynb` for Hebrew.

Data: the bike-share days above and an extract of the World Bank World Development Indicators (CC BY 4.0).

## Reading web pages with requests and Beautiful Soup (arXiv hardware papers)

The practice notebooks of three lessons that form one set: [From a Web Page to Data: Beautiful Soup](https://dvirross.com/courses/intro-data-science/data-collection-beautifulsoup) (part 1, tasks 1 to 3), [From One Element to All Entries](https://dvirross.com/courses/intro-data-science/data-collection-find-all) (part 2, tasks 4 to 6) and [From a List to Many Pages](https://dvirross.com/courses/intro-data-science/data-collection-linked-pages) (part 3, tasks 7 to 9). The code reads saved copies of arXiv pages that are kept on dvirross.com, so the checks give the same result for everyone; the cells marked "Live site" read arXiv itself, with a user agent of their own, and their numbers change from day to day.

| Notebook | Open in Colab |
|---|---|
| English, tasks | [data-collection-bs4.ipynb](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4.ipynb) |
| English, solutions | [data-collection-bs4-solutions.ipynb](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4-solutions.ipynb) |
| Hebrew, tasks | [data-collection-bs4.he.ipynb](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4.he.ipynb) |
| Hebrew, solutions | [data-collection-bs4-solutions.he.ipynb](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4-solutions.he.ipynb) |

Data: the list of the Hardware Architecture section (cs.AR) of arXiv for October 2026 and eight paper pages, retrieved on 2026-11-13 and saved unchanged; the papers belong to their authors. The code is generated from the lesson pages, so the pages and the notebooks stay the same.

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

שיעורים: [טבלאות כאובייקטים ב-Python: היכרות ראשונה עם Pony ORM](https://dvirross.com/he/courses/intro-data-science/python-orm-pony) (חלק 1, משימות 1 עד 8) ו[Pony ORM: טבלה שמצביעה על טבלה אחרת](https://dvirross.com/he/courses/intro-data-science/python-orm-pony-relations) (חלק 2, משימות 9 עד 13). מחברת אחת מכסה את שני השיעורים, וכותרת מסמנת איפה כל חלק מתחיל. התא הראשון מתקין את Pony אם צריך, ותא ההכנה מוריד קובץ CSV קטן מהאתר. המחברות נגזרות מדפי השיעורים, ולכן למשימות אותו מספר וניסוח בדפים ובמחברת.

| שפה | משימות | פתרונות |
|---|---|---|
| עברית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.he.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.he.ipynb) |
| אנגלית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/orm-pony-bikeshare-worldbank-solutions.ipynb) |

## קריאת דפי אינטרנט עם requests ו-Beautiful Soup (מאמרי חומרה מ-arXiv)

שיעורים: [מדף אינטרנט לנתונים: Beautiful Soup](https://dvirross.com/he/courses/intro-data-science/data-collection-beautifulsoup) (חלק 1, משימות 1 עד 3), [מאלמנט אחד לכל הערכים](https://dvirross.com/he/courses/intro-data-science/data-collection-find-all) (חלק 2, משימות 4 עד 6) ו[מרשימה לדפים רבים](https://dvirross.com/he/courses/intro-data-science/data-collection-linked-pages) (חלק 3, משימות 7 עד 9). הקוד קורא עותקים שמורים של דפי arXiv ששמורים באתר, ולכן הבדיקות נותנות לכולם אותה תוצאה. התאים שמסומנים "האתר החי" קוראים את arXiv עצמו, והמספרים בהם משתנים מיום ליום.

| שפה | משימות | פתרונות |
|---|---|---|
| עברית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4.he.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4-solutions.he.ipynb) |
| אנגלית | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4.ipynb) | [פתיחה ב-Colab](https://colab.research.google.com/github/dvirross/intro-data-science-notebooks/blob/main/data-collection-bs4-solutions.ipynb) |
