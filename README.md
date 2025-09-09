# -1
病人安全週互動小遊戲
<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8" />
  <title>病人安全週｜病安小尖兵挑戰</title>
  <style>
    body { font-family: "Noto Sans", sans-serif; background: #f9f9f9; color: #333; padding: 1em; max-width: 600px; margin: auto; }
    h1 { text-align: center; }
    .tab { margin: 1em 0; display: flex; justify-content: space-around; }
    .tab button { padding: .5em 1em; border: none; background: #ddd; cursor: pointer; }
    .active { background: #bbb; }
    .section { display: none; }
    .visible { display: block; }
    .question { margin: 1em 0; }
    .choice { display: block; margin: .5em 0; padding: .5em; border: 1px solid #ccc; border-radius: 4px; cursor: pointer; }
    .correct { background: #e0ffe0; }
    .wrong { background: #ffe0e0; }
  </style>
</head>
<body>
  <h1>病人安全週｜病安小尖兵挑戰</h1>
  <div class="tab">
    <button id="qTab" class="active">闖關問答</button>
    <button id="mTab">拖曳配對</button>
    <button id="sTab">快問快答</button>
  </div>
  
  <!-- 闖關問答區 -->
  <div id="quiz" class="section visible">
    <div id="quizQ" class="question"></div>
    <div id="quizChoices"></div>
    <div id="quizResult"></div>
  </div>
  
  <!-- 拖曳配對區 -->
  <div id="match" class="section">
    <div id="matchTitle"></div>
    <div id="leftCol"></div>
    <div id="rightCol"></div>
    <div id="matchResult"></div>
  </div>
  
  <!-- 快問快答區 -->
  <div id="speed" class="section">
    <div id="timer">30 秒</div>
    <div id="speedQuestions"></div>
  </div>
  
  <script>
    // 這裡會寫題庫、互動邏輯、Tab 切換。
    // 我可以幫你把之前 React 裡的題庫內容與邏輯轉貼進這裡。
  </script>
</body>
</html>
