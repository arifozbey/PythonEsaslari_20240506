# Python Dili Esasları
![PythonLogo](https://www.python.org/static/img/python-logo@2x.png)

## Python Ortamının Hazırlanması
**Python** ortamını hazırlamak için:
1. Öncelikle [python.org](https://www.python.org/) sitesinden engine indirmek gerekli.
2. Sonrasında terminal üzerinden veya bir IDE ile çalışabilirsiniz.
    * `Jupyter Lab` , `Jupyter Notebook`
    * `Visual Studio Code`, `Spyder`, `PyCharm`
3. Dilerseniz **Anaconda** dağıtımını kurarak her şeyi derli toplu `Anaconda Navigator` ile yöntebilirsiniz.
4. ~Python2~ yerine *python3* kullanmaya dikkat edelim.

**Not:** 
* Yukarıdaki yatık tırnakları (`) <kbd>AltGr</kbd> + <kbd>;</kbd> + <kbd>Space</kbd> ile oluşturuldu.
* Markdown dili html kodlarını destekler. <font color='red'>Bu metin ile html ile yazıldı.</font>

## Çalışma Modları:
1. Interactive Mode
2. Script Mode
3. Setup Mode

## Kullananacağımız Bazı Komutlar
### Shell Komutları:

```shell
py --version
py --list
py -3.11
py3
    help()
    help(print)
    exit()
cls
```

### Python komuları
```python
print("merhaba", "dünyalı", sep="-",end="!")
```

### SQL Komutları
```sql
SELECT
    kolon1,
    kolon2
FROM TabloAdi
```

## Bazı Kısayollar
* Hücrelerdeki kodları çalıştırırken.
    * <kbd>Shift</kbd> + <kbd>Enter</kbd> : Çalıştırır altta hücre yoksa boş açarsa varsa o hücreye geçer:
    * <kbd>Alt</kbd> + <kbd>Enter</kbd>: Çalıştırır alta boş hücre açar
    * <kbd>Ctrl</kbd> +<kbd>Enter</kbd>: Çalıştırır aynı hücrede kalır.
* Command Mode seçili iken mevcut hücre 
    * üzerine hücre eklemek için <kbd>A</kbd>, 
    * altına hücre eklemek için <kbd>B</kbd> 
    * hücreyi silmek için <kbd>D</kbd>, <kbd>D</kbd>
    * Tüm kısa yolları görmek için <kbd>H</kbd> kullanırız.
    
## Matematiksel Semboller Gösterilebilir
* https://rmd4sci.njtierney.com/math
* $x^2$
* $\int$
* $\infty$
* $\int_0^\infty x^{-a}$
* $\frac{1-x}{3-y}$
* $\sum_{i=1}^n$
* $\sqrt{1-p}$

## Tablo Oluşturma
|Ad| Soyad|
|----|-----|
|Ali |Uçan|
|Veli |Kaçan|
