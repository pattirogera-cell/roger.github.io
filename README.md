<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía Completa de C# 5.0</title>
    <!-- Estilos CSS -->
    <style>
        :root {
            --bg-color: #1e1e1e;
            --card-bg: #252526;
            --text-color: #d4d4d4;
            --accent-color: #007acc;
            --keyword-color: #569cd6;
            --string-color: #ce9178;
            --comment-color: #6a9955;
            --type-color: #4ec9b0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        h1 {
            color: #ffffff;
            margin-bottom: 5px;
        }

        .subtitle {
            color: #888;
            font-style: italic;
        }

        .section {
            background-color: var(--card-bg);
            border-radius: 8px;
            padding: 20px 25px;
            margin-bottom: 25px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }

        h2 {
            color: var(--accent-color);
            border-bottom: 1px solid #3c3c3c;
            padding-bottom: 8px;
        }

        pre {
            background-color: #1e1e1e;
            border: 1px solid #3c3c3c;
            border-radius: 5px;
            padding: 15px;
            overflow-x: auto;
            font-family: 'Consolas', 'Courier New', Courier, monospace;
            font-size: 14px;
        }

        /* Coloreado de sintaxis simulado (Estilo VS Code / Visual Studio) */
        .kw { color: var(--keyword-color); font-weight: bold; } /* Keywords */
        .str { color: var(--string-color); }                  /* Strings */
        .com { color: var(--comment-color); }                 /* Comments */
        .typ { color: var(--type-color); }                    /* Types */

        .badge {
            background-color: var(--accent-color);
            color: white;
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 12px;
            vertical-align: middle;
