# Bible-Dataset
Dataset of the Indonesian NT Bible

The dataset consists of Indonesian Bible verses labeled as either **PL** (Perjanjian Lama – Old Testament) or **PB** (Perjanjian Baru – New Testament).

📌 Sample (First 5 rows):

| id | kitab | pasal | ayat | firman |
|----|-------|-------|------|--------|
| 1  | Kej   | 1     | 1    | Pada mulanya Allah menciptakan langit dan bumi. |
| 2  | Kej   | 1     | 2    | Bumi belum berbentuk dan kosong; gelap gulita... |
| 3  | Kej   | 1     | 3    | Berfirmanlah Allah: "Jadilah terang." Lalu terang itu jadi. |
| 4  | Kej   | 1     | 4    | Allah melihat bahwa terang itu baik... |
| 5  | Kej   | 1     | 5    | Dan Allah menamai terang itu siang... |

📁 Files:

- `Bible-Dataset/tb.csv` – full dataset

🗃️ Dataset access
Use this simple script:
_
import pandas as pd
url  = "https://raw.githubusercontent.com/MarthenSS/Bible-Dataset/main/tb.csv"
data = pd.read_csv(url)

print(data.head())_

You can also access it from your browser. Click the link below to see the raw data:
[Raw Data CSV] (https://raw.githubusercontent.com/MarthenSS/Bible-Dataset/main/tb.csv)

---
