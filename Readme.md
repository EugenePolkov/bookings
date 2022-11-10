# Power BI отчет по демонстрационной базе данных пассажирских авиаперевозок в России от Postgres

Отчет сделан по мотивам заметки на Хабре о том, как разработчки Postgres  создавали демонстрационную базу данных https://habr.com/ru/company/postgrespro/blog/316428/ 

Поскольку подробных открытых данных по российским авиаперевозкам нет, то с одной стороны интересно посмотреть как мог бы выглядеть дашборд со сводными показателями по всему рынку, а с другой стороны интересно посмотреть насколько информация в базе правдоподобна: ведь разработчики заявляли, что пытались наполнить базу данными близкими  к реальности.  

Для отчета выбран сэмпл данных medium, который  охватывает период с середины июля по середину ноября 2016г. Исходные данные были загружены в Postgres, из которой они были импортированы в Power BI.  

Также есть отдельная версия для web c заглушками для элементов, которые не поддерживаются при публикации в интернете - [ссылка](https://app.powerbi.com/view?r=eyJrIjoiN2UxMzJhMDEtOTUxNC00ZDg5LWE1ZGEtYjkxN2FmMTE3MWI3IiwidCI6IjU5OGVhN2U3LTc5OWYtNDUyZi1iNGU3LTQwMzFjMzc0MTJjYyIsImMiOjl9) 
