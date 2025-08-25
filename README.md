airdrops = {
    '0xAddress1': 100,  # آدرس کیف پول و تعداد توکن
    '0xAddress2': 50,
    '0xAddress3': 200,
    '0xAddress4': 7,
}
# آدرس کیف پول فرستنده (کیف پول پروژه)
sender_address = '0xProjec,Wallet'

# نام توکن
token_name = 'MyToken'

print(f" شروع فرآیند ایردراپ توکن‌های {token_name} از آدرس {sender_address}\n")

# پیمایش در دیکشنری و نمایش تراکنش‌ه
for address, amount in airdrops.items():
    print(f"ارسال {amount} توکن {token_name} به آدرس {address}")
    
