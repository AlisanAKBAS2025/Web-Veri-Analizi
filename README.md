# Nalburdayım Ürün Verisi Çekme ve Excel'e Yazdırma

Bu proje, [Nalburdayım](https://www.nalburdayim.com) sitesinden ürün verilerini çekip, bu verileri istenilen bir Excel dosyasına yazdırmanıza olanak tanır. Proje, Selenium ve BeautifulSoup kullanarak web scraping yapar ve pandas kullanarak verileri Excel dosyasına yazar.

## Özellikler

- Nalburdayım sitesindeki ürün verilerini çekme
- Ürün verilerini belirtilen bir Excel dosyasına yazdırma
- Ürün adı, marka, fiyat, döviz türü, KDV oranı ve ürün fotoğrafı URL'si bilgilerini çekme

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki yazılımların sisteminizde kurulu olması gerekmektedir:

- [Python 3.7+](https://www.python.org/downloads/)
- Python kütüphaneleri:
  - `beautifulsoup4`
  - `selenium`
  - `pandas`
  - `openpyxl`
- [Google Chrome](https://www.google.com/chrome/) tarayıcısı
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)

Gerekli Python kütüphanelerini yüklemek için şu komutu kullanabilirsiniz:

```sh
pip install beautifulsoup4 selenium pandas openpyxl
