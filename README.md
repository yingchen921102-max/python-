``` python

# python-# main.py - 我們的專案骨架

# ===== 邏輯設計與除錯相關 (A,B 同學負責) =====
#設計程式主要架構、計分邏輯、題目結構(如用list/dict)、除錯與測試
def save_data(data):
    # TODO: B 同學在這裡實作存檔邏輯
    print("功能開發中：儲存資料...")
    pass

def load_data():
    # TODO: B 同學在這裡實作讀檔邏輯
    print("功能開發中：讀取資料...")
    return []

# ===== 內容設計相關 (C 同學負責) =====
#設計題目與邏輯、美化輸出結果
def add_expense(data):
    # TODO: A 同學在這裡實作新增支出邏輯
    print("功能開發中：新增支出...")
    pass

def view_expenses(data):
    # TODO: A 同學在這裡實作查看紀錄邏輯
    print("功能開發中：查看紀錄...")
    pass

def calculate_total(data):
    # TODO: C 同學在這裡實作計算總計邏輯
    print("功能開發中：計算總計...")
    pass

# ===== 主程式流程 (大家一起討論決定) =====
def main():
    my_expenses = load_data()
    # ... 這裡可以放選單邏輯 ...
    view_expenses(my_expenses)

# 程式執行入口
if __name__ == "__main__":
    main()

```
