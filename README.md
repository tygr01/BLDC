# BLDC
2024 Teknofest Efficiency Challenge yarışlarında kullanılmak üzere Zeugma Elektrikli aracı için tasarlanmıştır. Aracın 4 çeker olması sebebiyle 4 adet üretimi yapılmıştır. Takım tarafından geliştirilen yazılım ile araç üzerinde kullanılmıştır. Yazılım ve donanım tarafındaki eksikleri nedeniyle tam olarak başarıya ulaşamamıştır. Tasarımda kullanılan mosfetlerin yükünün azaltılması için 3 paralel mosfet toplamda 18 mosfet kullanılmıştır. Bu mosfetlerin açılması için yüksek akım özellikli kapı sürücüleri ve buna uygun kapı sürücü devresi tasarlanmışıtr. 
![ZEUGMA_EC](https://github.com/user-attachments/assets/1e3d0aaf-86cc-462e-8a27-7462cef7915e)

12V ihtiyacı kart üzerinde tasarlanan buck converter devresi üzerinden sağlanmaktadır. Bu doğrultuda 15 ile 100 volt arasında 12V 1A çıkış elde edilebilmektedir. Ana akım ölçümü için ACS758LCB-100B-PFF-T kullanılmıştır. 
Motor sürücünün genel özellikleri aşağıda verilmişitir.
- MCU: STM32F103CBT6
- MOSFET: IXTH130N10T
- UCC27201
- POWER: 3kW
- BUCK: LM5164
- CONTROL:TRAPEZOIDAL.
