NFL Play by Play Veri Temizleme Projesi / NFL Play by Play Data Cleaning Project

Proje Açıklaması / Project Description
Bu proje, NFL’in 2009-2016 yılları arasındaki oyun verilerini temizlemeyi ve analiz etmeyi amaçlamaktadır. Veri temizleme sürecinde eksik değerler doldurulmuş, veri tipleri düzeltilmiş ve potansiyel aykırı değerler incelenmiştir.
This project aims to clean and analyze NFL play-by-play data from 2009 to 2016. The data cleaning process includes filling missing values, correcting data types, and identifying potential outliers.

Veri / Data
Ham veri dosyası yaklaşık 200 MB boyutundadır ve GitHub’a dahil edilmemiştir. Dosya Google Drive üzerinden erişilebilir:
The raw dataset is approximately 200 MB and is not included in this repository. It can be accessed via Google Drive:
NFL Play by Play 2009-2016

Veriyi yüklemek için notebook içinde aşağıdaki kod kullanılabilir:
To load the data in the notebook, use the following code:

"import pandas as pd
url = "https://drive.google.com/drive/folders/16nOmk08YPNZfrYgGio5yVEV5loTJnUeX?usp=sharing"
df = pd.read_csv(url)"

Kurulum / Setup
Anaconda veya başka bir Python ortamı kurun / Install Anaconda or another Python environment
Gerekli kütüphaneleri yükleyin / Install required libraries:
pip install pandas numpy matplotlib seaborn
Notebook’u açın ve veriyi yükleyin / Open the notebook and load the data

Kullanım / Usage
Eksik değerler doldurulmuş ve veri tipleri düzeltilmiş halini inceleyebilirsiniz / Explore the dataset with missing values filled and correct data types
Potansiyel aykırı değerler analiz edilmiştir / Potential outliers have been identified
Notebook’ta çeşitli veri görselleştirmeleri ve özet tablolar bulunmaktadır / Notebook contains data visualizations and summary tables

Notlar / Notes
Veriyi indirmek ve notebook’u çalıştırmak için internet bağlantısı gereklidir / An internet connection is required to download the data and run the notebook
Daha büyük veri setleri ile çalışırken sistem kaynakları zorlanabilir / Working with large datasets may consume significant system resources
