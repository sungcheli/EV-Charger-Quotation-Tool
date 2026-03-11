# LV2
# 充電樁簡易報價整理工具

# 輸入資料
item_name = input("請輸入品名：")
quantity = int(input("請輸入數量："))
unit_price = float(input("請輸入單價："))

# 計算金額
subtotal = quantity * unit_price
tax = subtotal * 0.05
total = subtotal + tax

# 輸出結果
print("\n====== 報價結果 ======")
print(f"品名：{item_name}")
print(f"數量：{quantity}")
print(f"單價：{unit_price:,.0f} 元")
print(f"未稅小計：{subtotal:,.0f} 元")
print(f"稅額(5%)：{tax:,.0f} 元")
print(f"含稅總價：{total:,.0f} 元")

# 報價摘要
summary = f"{item_name} x {quantity}，單價 {unit_price:,.0f} 元，未稅 {subtotal:,.0f} 元，含稅總價 {total:,.0f} 元。"
print("\n報價摘要：")
print(summary)
