<!DOCTYPE html>
<html>
<head>
  <title></title>
  <style>
    .square {
      width: 500px;
      height: 300px;
      background-color: transparent;
      border: 2px solid black;
      border-radius: 20px;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .big-rectangle {
      width: 400px;
      height: 170px;
      background-color: transparent;
      border: 2px solid black;
      position: absolute;
      top: 35%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 80px;
      text-align: center;
    }

    .small-rectangle {
      width: 110px;
      height: 50px;
      background-color: transparent;
      border: 2px solid black;
      position: absolute;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 30px;
      text-align: center;
      cursor: pointer; 
    }

   
    .small-rectangle:nth-child(2) {
      top: 220px;
      left: calc(15% - 60px);
    }

    .small-rectangle:nth-child(3) {
      top: 220px;
      left: calc(37% + 10px);
    }

    .small-rectangle:nth-child(4) {
      top: 220px;
      left: calc(50% + 130px);
    }
  </style>
</head>
<body>

<div class="square">
  <div class="big-rectangle"><span id="timer">00:00:00</span></div>
  <div class="small-rectangle" onclick="startTimer()"><span>START</span></div>
  <div class="small-rectangle" onclick="stopTimer()"><span>STOP</span></div>
  <div class="small-rectangle" onclick="resetTimer()"><span>RESET</span></div>
</div>

<script>
  let timerRunning = false;
  let startTime;
  let elapsedTime = 0;
  let timerInterval;

  function startTimer() {
    if (!timerRunning) {
      timerRunning = true;
      startTime = Date.now() - elapsedTime;
      timerInterval = setInterval(updateTimer, 1000);
    }
  }

  function stopTimer() {
    if (timerRunning) {
      timerRunning = false;
      clearInterval(timerInterval);
      elapsedTime = Date.now() - startTime;
    }
  }

  function resetTimer() {
    stopTimer();
    elapsedTime = 0;
    document.getElementById('timer').innerText = '00:00:00';
  }

  function updateTimer() {
    const currentTime = Date.now() - startTime;
    const hours = Math.floor(currentTime / 3600000);
    const minutes = Math.floor((currentTime % 3600000) / 60000);
    const seconds = Math.floor((currentTime % 60000) / 1000);

    document.getElementById('timer').innerText = `${String(hours).padStart(2, '0')}:${String(minutes).padStart(2, '0')}:${String(seconds).padStart(2, '0')}`;
  }
</script>

</body>
</html>
