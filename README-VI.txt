HUONG DAN DICH NGUOC NRO-OFFLINE BANG GITHUB ACTIONS

1. Tao mot repository GitHub moi (nen de Private neu JAR la tep rieng).
2. Giai nen goi nay tren dien thoai/may tinh.
3. Upload file workflow:
   .github/workflows/decompile.yml
   len repository, dung dung duong dan nhu tren.
4. Upload file game cua ban vao thu muc goc repository va doi ten chinh xac:
   NRO-Offline-1.0.4.jar
5. Commit/push cac file len nhanh main.
6. Mo tab Actions tren GitHub.
7. Chon workflow "Decompile NRO JAR".
8. Neu workflow chua tu chay, chon Run workflow -> Run workflow.
9. Cho workflow chay xong (dau xanh).
10. Mo lan chay do, keo xuong muc Artifacts va tai:
    NRO-Offline-1.0.4-decompiled
11. Giai nen ZIP. Ma Java nam trong thu muc decompiled.

LUU Y
- Workflow nay chi dich nguoc de tao ma .java de doc/nghien cuu; khong tu dong
  sua game va khong dam bao ma dich nguoc co the bien dich lai ngay.
- CFR co the khong phuc hoi duoc ten bien/ten ham goc, comment hoac cau truc
  da bi lam roi. Mot so lop Java ME/MIDP co the can chinh sua thu cong.
- Khong commit/push tep neu ban khong co quyen su dung/chia se no.
- Khong dua token, mat khau hoac khoa truy cap vao repository.
