# Clase-01-Proyecto-Base-Python.

PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> cd "C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python"
PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> Get-ChildItem .venv\Scripts


    Directorio: C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python\.venv\Scripts


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l      22/10/2025  7:55 a. m.           2254 activate
-a---l      22/10/2025  7:55 a. m.           1045 activate.bat
-a---l      22/10/2025  7:55 a. m.           2304 activate.fish
-a---l      14/08/2025  3:34 p. m.           9031 Activate.ps1
-a---l      14/08/2025  3:33 p. m.            393 deactivate.bat
-a---l      22/10/2025  7:55 a. m.         108416 pip.exe
-a---l      22/10/2025  7:55 a. m.         108416 pip3.13.exe
-a---l      22/10/2025  7:55 a. m.         108416 pip3.exe
-a---l      14/08/2025  3:33 p. m.         255320 python.exe
-a---l      14/08/2025  3:33 p. m.         251736 pythonw.exe


PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Force
PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> . .venv\Scripts\Activate.ps1
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> python --version
Python 3.13.7
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip list
Package Version
------- -------
pip     25.2
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip install pandas
Collecting pandas
  Using cached pandas-2.3.3-cp313-cp313-win_amd64.whl.metadata (19 kB)
Collecting numpy>=1.26.0 (from pandas)
  Using cached numpy-2.3.4-cp313-cp313-win_amd64.whl.metadata (60 kB)
Collecting python-dateutil>=2.8.2 (from pandas)
  Using cached python_dateutil-2.9.0.post0-py2.py3-none-any.whl.metadata (8.4 kB)
Collecting pytz>=2020.1 (from pandas)
  Using cached pytz-2025.2-py2.py3-none-any.whl.metadata (22 kB)
Collecting tzdata>=2022.7 (from pandas)
  Using cached tzdata-2025.2-py2.py3-none-any.whl.metadata (1.4 kB)
Collecting six>=1.5 (from python-dateutil>=2.8.2->pandas)
  Using cached six-1.17.0-py2.py3-none-any.whl.metadata (1.7 kB)
Using cached pandas-2.3.3-cp313-cp313-win_amd64.whl (11.0 MB)
Using cached numpy-2.3.4-cp313-cp313-win_amd64.whl (12.8 MB)
Using cached python_dateutil-2.9.0.post0-py2.py3-none-any.whl (229 kB)
Using cached pytz-2025.2-py2.py3-none-any.whl (509 kB)
Using cached six-1.17.0-py2.py3-none-any.whl (11 kB)
Using cached tzdata-2025.2-py2.py3-none-any.whl (347 kB)
Installing collected packages: pytz, tzdata, six, numpy, python-dateutil, pandas
Successfully installed numpy-2.3.4 pandas-2.3.3 python-dateutil-2.9.0.post0 pytz-2025.2 six-1.17.0 tzdata-2025.2                                                
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip install matplotlib
Collecting matplotlib
  Downloading matplotlib-3.10.7-cp313-cp313-win_amd64.whl.metadata (11 kB)
Collecting contourpy>=1.0.1 (from matplotlib)
  Downloading contourpy-1.3.3-cp313-cp313-win_amd64.whl.metadata (5.5 kB)
Collecting cycler>=0.10 (from matplotlib)
  Downloading cycler-0.12.1-py3-none-any.whl.metadata (3.8 kB)
Collecting fonttools>=4.22.0 (from matplotlib)
  Downloading fonttools-4.60.1-cp313-cp313-win_amd64.whl.metadata (114 kB)
Collecting kiwisolver>=1.3.1 (from matplotlib)
  Downloading kiwisolver-1.4.9-cp313-cp313-win_amd64.whl.metadata (6.4 kB)
Requirement already satisfied: numpy>=1.23 in c:\users\aleja\onedrive\desktop\clase-01-proyecto-base-python\.venv\lib\site-packages (from matplotlib) (2.3.4)
Collecting packaging>=20.0 (from matplotlib)
  Downloading packaging-25.0-py3-none-any.whl.metadata (3.3 kB)
Collecting pillow>=8 (from matplotlib)
  Downloading pillow-12.0.0-cp313-cp313-win_amd64.whl.metadata (9.0 kB)
Collecting pyparsing>=3 (from matplotlib)
  Downloading pyparsing-3.2.5-py3-none-any.whl.metadata (5.0 kB)
Requirement already satisfied: python-dateutil>=2.7 in c:\users\aleja\onedrive\desktop\clase-01-proyecto-base-python\.venv\lib\site-packages (from matplotlib) (2.9.0.post0)
Requirement already satisfied: six>=1.5 in c:\users\aleja\onedrive\desktop\clase-01-proyecto-base-python\.venv\lib\site-packages (from python-dateutil>=2.7->matplotlib) (1.17.0)
Downloading matplotlib-3.10.7-cp313-cp313-win_amd64.whl (8.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.1/8.1 MB 5.2 MB/s  0:00:01
Downloading contourpy-1.3.3-cp313-cp313-win_amd64.whl (226 kB)
Downloading cycler-0.12.1-py3-none-any.whl (8.3 kB)
Downloading fonttools-4.60.1-cp313-cp313-win_amd64.whl (2.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 6.8 MB/s  0:00:00
Downloading kiwisolver-1.4.9-cp313-cp313-win_amd64.whl (73 kB)
Downloading packaging-25.0-py3-none-any.whl (66 kB)
Downloading pillow-12.0.0-cp313-cp313-win_amd64.whl (7.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 7.0/7.0 MB 7.1 MB/s  0:00:00
Downloading pyparsing-3.2.5-py3-none-any.whl (113 kB)
Installing collected packages: pyparsing, pillow, packaging, kiwisolver, fonttools, cycler, contourpy, matplotlib
Successfully installed contourpy-1.3.3 cycler-0.12.1 fonttools-4.60.1 kiwisolver-1.4.9 matplotlib-3.10.7 packaging-25.0 pillow-12.0.0 pyparsing-3.2.5           
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip list
Package         Version
--------------- -----------
contourpy       1.3.3
cycler          0.12.1
fonttools       4.60.1
kiwisolver      1.4.9
matplotlib      3.10.7
numpy           2.3.4
packaging       25.0
pandas          2.3.3
pillow          12.0.0
pip             25.2
pyparsing       3.2.5
python-dateutil 2.9.0.post0
pytz            2025.2
six             1.17.0
tzdata          2025.2
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> notepad test_matplotlib.py
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> plt.plot([1, 2, 3, 4], [10, 20, 25, 30])
En línea: 1 Carácter: 11
+ plt.plot([1, 2, 3, 4], [10, 20, 25, 30])
+           ~
Falta el nombre de tipo después de '['.
En línea: 1 Carácter: 12
+ plt.plot([1, 2, 3, 4], [10, 20, 25, 30])
+            ~
Falta un argumento en la lista de parámetros.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : MissingTypename

(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> plt.title("Prueba de Matplotlib")
plt.title : El término 'plt.title' no se reconoce como nombre de un cmdlet, función, archivo de script o programa ejecutable. Compruebe si escribió 
correctamente el nombre o, si incluyó una ruta de acceso, compruebe que dicha ruta es correcta e inténtelo de nuevo.
En línea: 1 Carácter: 1
+ plt.title("Prueba de Matplotlib")
+ ~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (plt.title:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> plt.xlabel("Eje X")
plt.xlabel : El término 'plt.xlabel' no se reconoce como nombre de un cmdlet, función, archivo de script o programa ejecutable. Compruebe si escribió 
correctamente el nombre o, si incluyó una ruta de acceso, compruebe que dicha ruta es correcta e inténtelo de nuevo.
En línea: 1 Carácter: 1
+ plt.xlabel("Eje X")
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (plt.xlabel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> plt.ylabel("Eje Y")
plt.ylabel : El término 'plt.ylabel' no se reconoce como nombre de un cmdlet, función, archivo de script o programa ejecutable. Compruebe si escribió 
correctamente el nombre o, si incluyó una ruta de acceso, compruebe que dicha ruta es correcta e inténtelo de nuevo.
En línea: 1 Carácter: 1
+ plt.ylabel("Eje Y")
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (plt.ylabel:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip install openpyxl
Collecting openpyxl
  Downloading openpyxl-3.1.5-py2.py3-none-any.whl.metadata (2.5 kB)
Collecting et-xmlfile (from openpyxl)
  Downloading et_xmlfile-2.0.0-py3-none-any.whl.metadata (2.7 kB)
Downloading openpyxl-3.1.5-py2.py3-none-any.whl (250 kB)
Downloading et_xmlfile-2.0.0-py3-none-any.whl (18 kB)
Installing collected packages: et-xmlfile, openpyxl
Successfully installed et-xmlfile-2.0.0 openpyxl-3.1.5                                                                                                          
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip list
Package         Version
--------------- -----------
contourpy       1.3.3
cycler          0.12.1
et_xmlfile      2.0.0
fonttools       4.60.1
kiwisolver      1.4.9
matplotlib      3.10.7
numpy           2.3.4
openpyxl        3.1.5
packaging       25.0
pandas          2.3.3
pillow          12.0.0
pip             25.2
pyparsing       3.2.5
python-dateutil 2.9.0.post0
pytz            2025.2
six             1.17.0
tzdata          2025.2
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip install -r requirements.txt
ERROR: Could not open requirements file: [Errno 2] No such file or directory: 'requirements.txt'
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pwd

Path
----
C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python


(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> notepad requirements.txt
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> pip freeze > requirements.txt
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> notepad requirements.txt
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> git --version
git version 2.51.0.windows.2
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> git init                                               
Initialized empty Git repository in C:/Users/aleja/OneDrive/Desktop/Clase-01-Proyecto-Base-Python/.git/
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python> notepad .gitignore
(.venv) PS C:\Users\aleja\OneDrive\Desktop\Clase-01-Proyecto-Base-Python>       
