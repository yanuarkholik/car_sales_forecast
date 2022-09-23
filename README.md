# Car Sales Forecast

## Hasil peramalan
| RMSE  | MAE | R2 |
| ------------- | ------------- | ------------- |
| 4081.24180573 | 19775.38147969 | 0.99931414 |

Dapat dilihat bahwa RMSE dan MAE sangat buruk akan tetapi scatter plot hasil prediksi vs data asli mengatakan hasil dari peramalan sangat baik karena membentuk garis linear antara hasil peramlaan vs data asli.
![Hasil peramalan vs data asli](https://github.com/yanuarkholik/car_sales_forecast/blob/main/image/scatter%20plot.png)

Oleh sebab itu saya menyimpulkan bahwa metrik pengukuran yang digunakan kurang tepat, karena RMSE dan MAE sensitif terhadap outlier. Untuk itu metrik pengukuran R2 ditambahkan dan kecocokan data hasil peramalan dengan data  asli adalah  99,93 persen.
