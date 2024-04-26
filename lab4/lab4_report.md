University: ITMO University \
Faculty: FTMI Course: Cloud platforms as the basis of technology entrepreneurship \
Year: 2024 \
Group: U4125\
Author: Bodrov Maxim Sergeevich\
Lab: Lab3 \
Date of create: 26.04.2024 \
Date of finished: --.04.2024

Отчет по лабораторной работе №3
Схема:\
![image](https://github.com/MaxBodr/2024_2025-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-Bodrov_Maxim_S/assets/125296807/beaa5979-02e7-4934-a296-1be6070adb1d)

Начальное состояние (20-50 пользователей):\
ВМ: f1-micro (0.2 vCPU, 0.6 GB памяти) — около $4-6/мес.\
Cloud SQL: db-f1-micro (1 vCPU, 0.6 GB) — примерно $7/мес.\
Хранение: Standard Persistent Disk — $0.040/GB/мес., предположим 10GB — $0.40/мес.\

Тестирование партнерами (150-200 пользователей):\
ВМ: g1-small (0.5 vCPU, 1.7 GB памяти) — примерно $13-17/мес.\
Cloud SQL: db-g1-small (1 vCPU, 1.7 GB) — около $25/мес.\
Хранение: предположим 20GB — $0.80/мес.

Продовое решение (300+ пользователей):\
ВМ: n1-standard-1 (1 vCPU, 3.75 GB памяти) — примерно $24-30/мес.\
Cloud SQL: db-n1-standard-1 (1 vCPU, 3.75 GB) — около $30/мес.\
Хранение: предположим 50GB — $2/мес.

Общая стоимость в месяц:\
Начальное состояние: $11.40 - $13.40\
Тестирование партнерами: $38.80 - $42.80\
Продовое решение: $56 - $62

В основном буду использовать серверлесс-решения или управляемые сервисы (например, Cloud Functions для бота, Firestore для БД), которые минимизируют управленческие издержки и позволяют платить только за то, что использую (Так как сервис предпологает не постоянную нагрузку, а вызов скрипта при использовании бота)
