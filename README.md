# Phân Loại Nấm Ăn Được
## Tổng Quan
Dự án này là một phần của đồ án cuối khóa học Machine Learning.Mục tiêu là phân loại nấm là ăn được hay độc dựa trên các đặc điểm khác nhau.

Bộ dữ liệu được sử dụng cho nhiệm vụ phân loại này là bộ dữ liệu Nấm từ https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset

### Bộ Dữ Liệu
Bộ dữ liệu chứa các đặc điểm mô tả đặc tính vật lý của nấm.
- cap-diameter: Đường kính mũ nấm
- cap-shape: Hình dạng mũ nấm
- gill-attachment: Vị trí bám của mang nấm
- gill-color: Màu sắc của mang nấm
- stem-height: Chiều cao của thân nấm
- stem-width: Chiều rộng của thân nấm
- stem-color: Màu sắc của thân nấm
- season: Mùa nấm mọc
- class: Loại nấm ( Ăn được hoặc có độc)

Mỗi mẫu nấm được gán nhãn là ăn được hoặc độc.

### Cài Đặt
Để bắt đầu với dự án này, bạn cần cài đặt các thư viện cần thiết.

Sử dụng các lệnh sau để cài đặt các gói yêu cầu:
```
$ pip install pandas
$ pip install numpy
$ pip install matplotlib
$ pip install seaborn
$ pip install scikit-learn
```
### Cấu Trúc Dự Án
./Data/mushroom_cleaned.csv: Thư mục chứa tệp bộ dữ liệu.


[Analyze_data.ipynb](https://github.com/hiendamvan/mushroom_edible_classification/blob/main/Analyze_data.ipynb) : Được sử dụng cho phân tích dữ liệu.

[Decision_tree.ipynb](https://github.com/hiendamvan/mushroom_edible_classification/blob/main/decision_tree.ipynb) : Mô hình Decision Tree

[Random_forest.ipynb](https://github.com/hiendamvan/mushroom_edible_classification/blob/main/random_forest.ipynb) : Mô hình Random Forest

[KNN_MODEL.ipynb](https://github.com/hiendamvan/mushroom_edible_classification/blob/main/KNN_MODEL.ipynb) :
Mô hình K-Nearest Neighbors

[SVM_model.ipynb](https://github.com/hiendamvan/mushroom_edible_classification/blob/main/SVM_model.ipynb) :
Mô hình SVM

[Boosting.ipynb](https://github.com/hiendamvan/mushroom_edible_classification/blob/main/Boosting.ipynb) : 
Mô hình Boosting

[Logistic_Regression.ipynb](https://github.com/hiendamvan/mushroom_edible_classification/blob/main/Logistic_Regression.ipynb) : Mô hình Logistic Regression

# Chạy project
```
git clone https://github.com/hiendamvan/mushroom_edible_classification.git
```


Cảm Ơn
Bộ dữ liệu Nấm được lấy từ https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset.

Dự án này được phát triển sau khi học Machine Learning.
