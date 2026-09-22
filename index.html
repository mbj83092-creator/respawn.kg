<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RESPAWN.KG | Игровой клуб Шопоков</title>
    <!-- Подключаем иконки FontAwesome -->
    <link rel="stylesheet" href="https://cloudflare.com">
    <style>
        /* Базовые настройки стиля */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Roboto, sans-serif;
            background-color: #050505;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            box-sizing: border-box;
        }

        .container {
            width: 100%;
            max-width: 430px; /* Размер под экраны смартфонов */
            padding: 25px 15px;
            text-align: center;
            box-sizing: border-box;
        }

        /* Большой красный логотип 'R' на фоне сверху */
        .bg-logo {
            font-size: 110px;
            font-weight: 900;
            color: #bd081c;
            line-height: 1;
            margin-bottom: -15px;
            font-style: italic;
            text-shadow: 0 0 20px rgba(189, 8, 28, 0.4);
            user-select: none;
            
            /* Анимация для логотипа */
            animation: fadeInDown 0.8s ease-out forwards;
        }

        /* Название клуба */
        .title {
            font-size: 32px;
            font-weight: 800;
            letter-spacing: 1px;
            margin: 0 0 5px 0;
            animation: fadeIn 1s ease-out forwards;
        }

        .title span {
            color: #bd081c;
        }

        /* Локация / Подзаголовок */
        .subtitle {
            font-size: 11px;
            color: #777777;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 25px;
            animation: fadeIn 1.2s ease-out forwards;
        }

        /* Блок графика работы */
        .work-time {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: rgba(189, 8, 28, 0.1);
            border: 1px solid rgba(189, 8, 28, 0.3);
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: #ffffff;
            margin-bottom: 25px;
            animation: scaleIn 0.5s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
        }

        /* Мигающая зеленая точка для эффекта "работаем прямо сейчас" */
        .work-time::before {
            content: '';
            display: inline-block;
            width: 8px;
            height: 8px;
            background-color: #00ff66;
            border-radius: 50%;
            box-shadow: 0 0 8px #00ff66;
            animation: blink 1.5s infinite;
        }

        /* Сетка кнопок */
        .links-container {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-bottom: 35px;
        }

        /* Общие стили кнопок с начальным скрытием для анимации */
        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            padding: 14px 20px;
            border-radius: 8px;
            font-size: 15px;
            font-weight: 600;
            letter-spacing: 0.5px;
            transition: all 0.2s ease;
            position: relative;
            box-sizing: border-box;
            
            opacity: 0;
            transform: translateY(20px);
            animation: slideUp 0.5s ease-out forwards;
        }

        /* Иконка внутри кнопки строго слева */
        .btn i {
            position: absolute;
            left: 20px;
            font-size: 16px;
        }

        /* Главная акцентная кнопка бронирования */
        .btn-booking {
            background: #bd081c;
            color: #ffffff;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            border: none;
            box-shadow: 0 4px 15px rgba(189, 8, 28, 0.4);
            animation-delay: 0.1s; /* Очередность появления */
        }

        .btn-booking:hover {
            background: #d60e24;
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(189, 8, 28, 0.6);
        }

        /* Обычные кнопки соцсетей */
        .btn-social {
            background: #0d0d0d;
            color: #ffffff;
            border: 1px solid #1a1a1a;
        }

        .btn-social:hover {
            border-color: #bd081c;
            background: #141414;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.4);
        }

        /* Задержки анимации для плавного поочередного появления кнопок */
        .btn-instagram { animation-delay: 0.2s; }
        .btn-telegram  { animation-delay: 0.3s; }
        .btn-whatsapp  { animation-delay: 0.4s; }
        .btn-tiktok    { animation-delay: 0.5s; }

        /* Разделитель ПРАЙС */
        .price-divider {
            font-size: 11px;
            color: #555555;
            text-transform: uppercase;
            letter-spacing: 4px;
            margin-bottom: 15px;
            opacity: 0;
            animation: fadeIn 0.5s ease-out forwards;
            animation-delay: 0.6s;
        }

        /* Сетка для карточек прайса */
        .price-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
            margin-bottom: 40px;
        }

        /* Карточка тарифов */
        .price-card {
            background: #0d0d0d;
            border: 1px solid #141414;
            border-radius: 8px;
            padding: 15px 12px;
            text-align: left;
            
            opacity: 0;
            transform: translateY(20px);
            animation: slideUp 0.6s ease-out forwards;
        }

        .card-pc  { animation-delay: 0.7s; }
        .card-ps5 { animation-delay: 0.8s; }

        /* Шапка карточки */
        .card-header {
            font-size: 14px;
            font-weight: 700;
            margin-bottom: 12px;
            display: flex;
            align-items: center;
            gap: 6px;
            border-bottom: 1px solid #1a1a1a;
            padding-bottom: 8px;
        }

        /* Список цен */
        .price-list {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            flex-direction: column;
            gap: 6px;
        }

        .price-item {
            font-size: 12px;
            color: #aaaaaa;
            display: flex;
            justify-content: space-between;
        }

        .price-item span {
            color: #ffffff;
            font-weight: 600;
        }

        /* Копирайт внизу */
        .footer {
            font-size: 10px;
            color: #333333;
            text-transform: uppercase;
            letter-spacing: 2px;
            opacity: 0;
            animation: fadeIn 0.5s ease-out forwards;
            animation-delay: 0.9s;
        }

        /* === КЛЮЧЕВЫЕ КАДРЫ ДЛЯ АНИМАЦИЙ === */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes scaleIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }

        @keyframes blink {
            0% { opacity: 0.4; }
            50% { opacity: 1; }
            100% { opacity: 0.4; }
        }
    </style>
</head>
<body>

    <div class="container">
        
        <!-- Логотип 'R' -->
        <div class="bg-logo">R</div>

        <!-- Заголовок -->
        <h1 class="title">respawn<span>.kg</span></h1>
        <div class="subtitle">Игровой клуб • Shopokov</div>

        <!-- Новый блок: График работы -->
        <div class="work-time">
            Работаем 24/7 без выходных
        </div>

        <!-- Кнопки навигации с анимацией поочередного выплывания -->
        <div class="links-container">
            
            <!-- Забронировать / ТГ -->
            <a href="https://t.me" target="_blank" class="btn btn-booking btn-book">
                <i class="fas fa-gamepad"></i>
                ЗАБРОНИРОВАТЬ / TELEGRAM
            </a>

            <!-- Instagram -->
            <a href="https://instagram.com" target="_blank" class="btn btn-social btn-instagram">
                <i class="fab fa-instagram"></i>
                Instagram
            </a>

            <!-- Telegram -->
            <a href="https://t.me" target="_blank" class="btn btn-social btn-telegram">
                <i class="fab fa-telegram-plane"></i>
                Telegram
            </a>

            <!-- WhatsApp -->
            <a href="https://wa.me" target="_blank" class="btn btn-social btn-whatsapp">
                <i class="fab fa-whatsapp"></i>
                WhatsApp
            </a>

            <!-- TikTok -->
            <a href="https://tiktok.com" target="_blank" class="btn btn-social btn-tiktok">
                <i class="fab fa-tiktok"></i>
                TikTok
            </a>

        </div>

        <!-- Блок Прайс -->
        <div class="price-divider">Прайс</div>
        
        <div class="price-grid">
            
            <!-- Тарифы PC -->
            <div class="price-card card-pc">
