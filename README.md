<!DOCTYPE html>
<html lang="hy">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Թեհմինե Անդրեասյան | Վեբ Ծրագրավորողի Պորտֆոլիո</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: #f8fafc;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
            width: 100%;
        }
        header {
            text-align: center;
            padding: 3rem 1rem;
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid #334155;
        }
        header h1 {
            color: #38bdf8;
            font-size: 2.8rem;
            margin-bottom: 0.5rem;
        }
        header p {
            color: #94a3b8;
            font-size: 1.3rem;
        }
        section {
            background: rgba(30, 41, 59, 0.8);
            margin: 1.5rem 0;
            padding: 2.5rem;
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        section h2 {
            color: #38bdf8;
            margin-bottom: 1.2rem;
            font-size: 1.8rem;
            border-bottom: 2px solid #334155;
            padding-bottom: 0.5rem;
        }
        section p {
            font-size: 1.1rem;
            color: #cbd5e1;
            line-height: 1.8;
        }
        .skills-grid, .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }
        .skill-card, .project-card {
            background: #334155;
            padding: 1.2rem;
            border-radius: 10px;
            border: 1px solid rgba(56, 189, 248, 0.2);
            transition: 0.3s;
        }
        .skill-card {
            text-align: center;
            font-weight: 600;
            color: #38bdf8;
        }
        .project-card h3 {
            color: #38bdf8;
            margin-bottom: 0.5rem;
        }
        .project-card p {
            font-size: 0.95rem;
            color: #94a3b8;
            margin-bottom: 1rem;
        }
        .skill-card:hover, .project-card:hover {
            transform: translateY(-3px);
            border-color: #38bdf8;
            background: #384155;
        }
        .btn {
            display: inline-block;
            background: linear-gradient(135deg, #38bdf8, #0ea5e9);
            color: #0f172a;
            padding: 0.7rem 1.5rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            font-size: 0.95rem;
            transition: 0.3s;
            box-shadow: 0 4px 15px rgba(56, 189, 248, 0.3);
        }
        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(56, 189, 248, 0.5);
        }
        footer {
            text-align: center;
            padding: 1.5rem;
            color: #64748b;
            font-size: 0.9rem;
            background: #0b1120;
        }
    </style>
</head>
<body>

    <header>
        <h1>Բարև, ես Թեհմինե Անդրեասյանն եմ</h1>
        <p>Սկսնակ Վեբ Ծրագրավորող և Ժամանակակից Կայքերի Ստեղծող</p>
    </header>

    <div class="container">
        <section>
            <h2>Իմ մասին</h2>
            <p>Ես մասնագիտանում եմ պարզ, ժամանակակից և արագ վեբ-կայքերի ստեղծման գործում։ Օգնում եմ փոքր բիզնեսներին և անհատներին ունենալ իրենց սեփական դեմքն ու պրոֆեսիոնալ ներկայությունը ինտերնետում։</p>
        </section>

        <section>
            <h2>Իմ Նախագծերը</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Անձնական Պորտֆոլիո</h3>
                    <p>Իմ առաջին ինտերակտիվ և ժամանակակից վեբ-կայքը՝ ստեղծված HTML5-ով և CSS3-ով։</p>
                    <a href="https://tehmineandreasyan1999.github.io/my-tehmine/" class="btn">Դիտել Կայքը</a>
                </div>
            </div>
        </section>

        <section>
            <h2>Իմ Հմտությունները</h2>
            <div class="skills-grid">
                <div class="skill-card">HTML5 & CSS3</div>
                <div class="skill-card">JavaScript Հիմունքներ</div>
                <div class="skill-card">Responsive Դիզայն</div>
                <div class="skill-card">UI/UX Ձևավորում</div>
            </div>
        </section>

        <section>
            <h2>Կապ Ինձ Հետ</h2>
            <p>Ցանկանում՞ ես պատվիրել կայք կամ համագործակցել ինձ հետ։ Գրիր ինձ կամ կապ հաստատիր ստորև նշված հասցեով:</p>
            <br>
            <a href=tehmineandreasyan75gmail.com class="btn">Գրել Ինձ Նամակ</a>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Թեհմինե Անդրեասյան։ Բոլոր իրավունքները պաշտպանված են։</p>
    </footer>

</body>
</html>
