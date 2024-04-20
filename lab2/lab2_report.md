University: ITMO University \
Faculty: FTMI Course: Cloud platforms as the basis of technology entrepreneurship \
Year: 2024 \
Group: U4125\
Author: Bodrov Maxim Sergeevich\
Lab: Lab2 \
Date of create: 20.04.2024 \
Date of finished: --.04.2024

Отчет по лабораторной работе №2
Для начала был создан сервис в cloud-run и запущен дефолтный сервис hello.
![image](https://github.com/MaxBodr/2024_2025-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-Bodrov_Maxim_S/assets/125296807/09d94800-4869-4cf5-8486-90e674bb1db8)

При переходе по ссылке предоставленной Cloud Run
![image](https://github.com/MaxBodr/2024_2025-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-Bodrov_Maxim_S/assets/125296807/aeae5fb7-732c-4dfc-a5c0-559a97f46ab6)

Видим в логах информацию о том когда сайт создается и можем заметить заходы на сайт
![image](https://github.com/MaxBodr/2024_2025-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-Bodrov_Maxim_S/assets/125296807/1cbd2351-8eb5-4afe-8495-03409417cb1b)

Так же можно отследить нагрузку на сервер:
![image](https://github.com/MaxBodr/2024_2025-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-Bodrov_Maxim_S/assets/125296807/8f4a19a9-baac-4632-b3a1-499019f51db1)

После смены порта на 8090, на сайте отображается новое имя версии, которая сейчас активна - mbodrov-hello-00002-wqd
![image](https://github.com/MaxBodr/2024_2025-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-Bodrov_Maxim_S/assets/125296807/d203c423-11b2-4f78-a550-4d815d91ce2f)

В метриках так же можем заметить засечки когда мы деплоим новую версию или меняем трафик с одной версии на другую
![image](https://github.com/MaxBodr/2024_2025-cloud-platforms-as-the-basis-of-technology-entrepreneurship-U4125-Bodrov_Maxim_S/assets/125296807/76313202-751d-4000-af16-1108a0a77860)

Таким образом, в Cloud Run можно быстро запустить свой сайт на облачных мощнастях и просто отслеживать нагрузки на сайт. Так же можно отслеживать логи в случаях ошибок
