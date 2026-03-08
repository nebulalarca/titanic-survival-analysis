# 🚢 Titanic Survival Analysis

1912'de batan Titanic gemisinde hayatta kalma üzerine veri analizi yaptım. 
Amacım veriye bakarak "Kim daha çok hayatta kaldı ve neden?" sorusunu yanıtlamak.

## Ne Yaptım?
Kaggle'ın Titanic veri setini kullanarak önce veriyi iyice inceledim — 
eksik veriler, dağılımlar, ilginç örüntüler. Sonra makine öğrenmesiyle 
hayatta kalma tahmini yapan bir model kurdum.

## Neler Keşfettim?
- Kadınların hayatta kalma oranı erkeklerin 4 katı 
- 1.sınıf yolcuların şansı 3.sınıfa göre çok daha yüksekti 
- Küçük aileler yalnız yolculara göre daha şanslıydı 
- Çocuklar öncelikli olarak kurtarıldı 

## Kullandıklarım
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Nasıl Çalıştırırsın?
1. Repoyu klonla
2. `titanic_eda.ipynb` dosyasını VSCode'da aç
3. Hücreleri sırayla çalıştır (Shift + Enter)

## 🔍 Repoyu İncelemek İsteyenler İçin

1. Repoyu klonla:
   git clone https://github.com/nebulalarca/titanic-survival-analysis.git

2. Klasöre gir:
   cd titanic-survival-analysis

3. Gerekli kütüphaneleri yükle:
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter

4. Notebook'u aç:
   jupyter notebook titanic_eda.ipynb

5. Hücreleri sırayla çalıştır (Shift + Enter)
```

Ekledikten sonra kaydet **(Cmd + S)**, sonra terminalde:
```
git add README.md
git commit -m "Update README with setup instructions"
git push

