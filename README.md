# Prx-Cod-Bot
import random
import string


total_passwords = 10000

passwords = []

for _ in range(total_passwords):
    # إنشاء كلمة مرور عشوائية بطول 12 حرفًا
    password = "PRX-R" + ''.join(random.choices(string.ascii_letters + string.digits, k=7)) + "V"
    passwords.append(password)

print(passwords[:1000000])ㅤ
