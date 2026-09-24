<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#07111f">

<title>CFB Stat Tracker</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #07111f;
  color: white;
}

header {
  background: #0d1b2a;
  padding: 18px;
  text-align: center;
  border-bottom: 2px solid #1e90ff;
}

header h1 {
  margin: 0;
  font-size: 25px;
}

header p {
  margin: 5px 0 0;
  color: #aab7c4;
}

nav {
  display: flex;
  overflow-x: auto;
  background: #0a1625;
  padding: 8px;
  gap: 8px;
}

nav button {
  white-space: nowrap;
  border: none;
  border-radius: 8px;
  padding: 11px 15px;
  background: #14263a;
  color: white;
  font-weight: bold;
}

nav button.active {
  background: #1e90ff;
}

main {
  padding: 15px;
  max-width: 900px;
  margin: auto;
}

.card {
  background: #0d1b2a;
  border: 1px solid #1c334b;
  border-radius: 12px;
  padding: 16px;
  margin-bottom: 15px;
}

h2 {
  margin-top: 0;
}

input,
select {
  width: 100%;
  padding: 12px;
  margin: 6px 0;
  border-radius: 8px;
  border: 1px solid #31506c;
  background: #091522;
  color: white;
}

button.primary {
  width: 100%;
  padding: 13px;
  margin-top: 8px;
  border: none;
  border-radius: 8px;
  background: #1e90ff;
  color: white;
  font-weight: bold;
}

.stat-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px;
}

.stat {
  background: #101f30;
  padding: 14px;
  border-radius: 10px;
  text-align: center;
}

.stat strong {
  display: block;
  font-size: 24px;
  color: #4db2ff;
}

.player {
  padding: 12px;
  background: #101f30;
  border-radius: 9px;
  margin-top: 8px;
}

.hidden {
  display: none;
}

table {
  width: 100%;
  border-collapse: collapse;
}

th,
td {
  padding: 9px;
  border-bottom: 1px solid #294157;
  text-align: left;
}

.small {
  color: #9eafbf;
  font-size: 13px;
}
</style>
</head>

<body>

<header>
  <h1>🏈 CFB Stat Tracker</h1>
  <p>College Football Statistics</p>
</header>

<nav>
  <button class="active" onclick="showPage('home', this)">Home</button>
  <button onclick="showPage('teams', this)">Teams</button>
  <button onclick="showPage('players', this)">Players</button>
  <button onclick="showPage('game', this)">Game Tracker</button>
  <button onclick="showPage('stats', this)">Stats</button>
</nav>

<main>

<!-- HOME -->
<section id="home">

  <div class="card">
    <h2>Dashboard</h2>
    <p>Track college football games and player statistics.</p>
  </div>

  <div class="stat-grid">
    <div class="stat">
      <strong id="teamCount">0</strong>
      Teams
    </div>

    <div class="stat">
      <strong id="playerCount">0</strong>
      Players
    </div>

    <div class="stat">
      <strong id="gameCount">0</strong>
      Games
    </div>

    <div class="stat">
      <strong id="playCount">0</strong>
      Plays
    </div>
  </div>

</section>


<!-- TEAMS -->
<section id="teams" class="hidden">

  <div class="card">
    <h2>Add Team</h2>

    <input id="teamName" placeholder="Team name">

    <select id="teamLevel">
      <option>FBS</option>
      <option>FCS</option>
      <option>Division II</option>
      <option>Division III</option>
    </select>

    <button class="primary" onclick="addTeam()">
      Add Team
    </button>
  </div>

  <div class="card">
    <h2>My Teams</h2>
    <div id="teamList"></div>
  </div>

</section>


<!-- PLAYERS -->
<section id="players" class="hidden">

  <div class="card">
    <h2>Add Player</h2>

    <input id="playerName" placeholder="Player name">

    <input id="playerNumber"
           type="number"
           placeholder="Jersey number">

    <select id="playerPosition">
      <option>QB</option>
      <option>RB</option>
      <option>WR</option>
      <option>TE</option>
      <option>OL</option>
      <option>DL</option>
      <option>EDGE</option>
      <option>LB</option>
      <option>CB</option>
      <option>S</option>
      <option>K</option>
      <option>P</option>
      <option>LS</option>
    </select>

    <select id="playerTeam">
      <option value="">Select team</option>
    </select>

    <button class="primary" onclick="addPlayer()">
      Add Player
    </button>
  </div>

  <div class="card">
    <h2>Players</h2>
    <div id="playerList"></div>
  </div>

</section>


<!-- GAME TRACKER -->
<section id="game" class="hidden">

  <div class="card">
    <h2>Game Tracker</h2>

    <input id="homeTeam"
           placeholder="Home team">

    <input id="awayTeam"
           placeholder="Away team">

    <button class="primary" onclick="startGame()">
      Start Game
    </button>
  </div>

  <div id="gameControls" class="card hidden">

    <h2 id="gameTitle"></h2>

    <div class="stat-grid">
      <div class="stat">
        <strong id="homeScore">0</strong>
        Home
      </div>

      <div class="stat">
        <strong id="awayScore">0</strong>
        Away
      </div>
    </div>

    <h3>Add Play</h3>

    <select id="playType">
      <option>Pass</option>
      <option>Rush</option>
      <option>Reception</option>
      <option>Tackle</option>
      <option>Sack</option>
      <option>Interception</option>
      <option>Fumble Recovery</option>
      <option>Field Goal</option>
      <option>Punt</option>
    </select>

    <input id="yards"
           type="number"
           placeholder="Yards">

    <button class="primary" onclick="addPlay()">
      Add Play
    </button>

    <p class="small">
      Plays entered: <span id="gamePlays">0</span>
    </p>

  </div>

</section>


<!-- STATS -->
<section id="stats" class="hidden">

  <div class="card">
    <h2>Statistics</h2>

    <div class="stat-grid">

      <div class="stat">
        <strong id="passingYards">0</strong>
        Passing Yards
      </div>

      <div class="stat">
        <strong id="rushingYards">0</strong>
        Rushing Yards
      </div>

      <div class="stat">
        <strong id="receivingYards">0</strong>
        Receiving Yards
      </div>

      <div class="stat">
        <strong id="tackles">0</strong>
        Tackles
      </div>

    </div>
  </div>

  <div class="card">
    <h2>Stat Log</h2>

    <table>
      <thead>
        <tr>
          <th>Play</th>
          <th>Yards</th>
        </tr>
      </thead>

      <tbody id="statTable"></tbody>
    </table>

  </div>

</section>

</main>


<script>

let teams = JSON.parse(localStorage.getItem("cfbTeams")) || [];
let players = JSON.parse(localStorage.getItem("cfbPlayers")) || [];
let games = JSON.parse(localStorage.getItem("cfbGames")) || [];
let plays = JSON.parse(localStorage.getItem("cfbPlays")) || [];

let currentGame = null;


function saveData() {

  localStorage.setItem("cfbTeams", JSON.stringify(teams));
  localStorage.setItem("cfbPlayers", JSON.stringify(players));
  localStorage.setItem("cfbGames", JSON.stringify(games));
  localStorage.setItem("cfbPlays", JSON.stringify(plays));

}


function showPage(page, button) {

  document.querySelectorAll("main > section")
    .forEach(section => section.classList.add("hidden"));

  document.getElementById(page)
    .classList.remove("hidden");

  document.querySelectorAll("nav button")
    .forEach(btn => btn.classList.remove("active"));

  button.classList.add("active");

  updateDashboard();
  renderTeams();
  renderPlayers();
  renderStats();

}


function addTeam() {

  const name =
    document.getElementById("teamName").value.trim();

  const level =
    document.getElementById("teamLevel").value;

  if (!name) {
    alert("Enter a team name.");
    return;
  }

  teams.push({
    id: Date.now(),
    name,
    level
  });

  document.getElementById("teamName").value = "";

  saveData();
  renderTeams();
  renderPlayers();
  updateDashboard();

}


function renderTeams() {

  const list = document.getElementById("teamList");

  list.innerHTML = "";

  if (teams.length === 0) {
    list.innerHTML =
      "<p class='small'>No teams added yet.</p>";
    return;
  }

  teams.forEach(team => {

    const div = document.createElement("div");

    div.className = "player";

    div.innerHTML = `
      <strong>${team.name}</strong>
      <div class="small">${team.level}</div>
    `;

    list.appendChild(div);

  });

}


function renderPlayers() {

  const select =
    document.getElementById("playerTeam");

  select.innerHTML =
    '<option value="">Select team</option>';

  teams.forEach(team => {

    select.innerHTML +=
      `<option value="${team.id}">
        ${team.name}
      </option>`;

  });


  const list =
    document.getElementById("playerList");

  list.innerHTML = "";

  players.forEach(player => {

    const team =
      teams.find(t => t.id == player.teamId);

    const div =
      document.createElement("div");

    div.className = "player";

    div.innerHTML = `
      <strong>#${player.number} ${player.name}</strong>
      <div class="small">
        ${player.position} •
        ${team ? team.name : "No Team"}
      </div>
    `;

    list.appendChild(div);

  });

}


function addPlayer() {

  const name =
    document.getElementById("playerName").value.trim();

  const number =
    document.getElementById("playerNumber").value;

  const position =
    document.getElementById("playerPosition").value;

  const teamId =
    document.getElementById("playerTeam").value;

  if (!name || !teamId) {

    alert("Enter a player name and select a team.");

    return;

  }

  players.push({

    id: Date.now(),
    name,
    number,
    position,
    teamId

  });

  document.getElementById("playerName").value = "";
  document.getElementById("playerNumber").value = "";

  saveData();
  renderPlayers();
  updateDashboard();

}


function startGame() {

  const home =
    document.getElementById("homeTeam").value.trim();

  const away =
    document.getElementById("awayTeam").value.trim();

  if (!home || !away) {

    alert("Enter both teams.");

    return;

  }

  currentGame = {

    id: Date.now(),
    home,
    away,
    homeScore: 0,
    awayScore: 0

  };

  games.push(currentGame);

  document.getElementById("gameTitle").textContent =
    `${away} @ ${home}`;

  document.getElementById("gameControls")
    .classList.remove("hidden");

  saveData();
  updateDashboard();

}


function addPlay() {

  if (!currentGame) {

    alert("Start a game first.");

    return;

  }

  const type =
    document.getElementById("playType").value;

  const yards =
    Number(document.getElementById("yards").value) || 0;

  plays.push({

    id: Date.now(),
    gameId: currentGame.id,
    type,
    yards

  });

  document.getElementById("yards").value = "";

  saveData();

  document.getElementById("gamePlays").textContent =
    plays.filter(p => p.gameId === currentGame.id).length;

  renderStats();
  updateDashboard();

}


function renderStats() {

  let passing = 0;
  let rushing = 0;
  let receiving = 0;
  let tacklesTotal = 0;

  const table =
    document.getElementById("statTable");

  table.innerHTML = "";

  plays.forEach(play => {

    if (play.type === "Pass")
      passing += play.yards;

    if (play.type === "Rush")
      rushing += play.yards;

    if (play.type === "Reception")
      receiving += play.yards;

    if (play.type === "Tackle")
      tacklesTotal++;

    const row =
      document.createElement("tr");

    row.innerHTML = `
      <td>${play.type}</td>
      <td>${play.yards}</td>
    `;

    table.appendChild(row);

  });

  document.getElementById("passingYards").textContent =
    passing;

  document.getElementById("rushingYards").textContent =
    rushing;

  document.getElementById("receivingYards").textContent =
    receiving;

  document.getElementById("tackles").textContent =
    tacklesTotal;

}


function updateDashboard() {

  document.getElementById("teamCount").textContent =
    teams.length;

  document.getElementById("playerCount").textContent =
    players.length;

  document.getElementById("gameCount").textContent =
    games.length;

  document.getElementById("playCount").textContent =
    plays.length;

}


renderTeams();
renderPlayers();
renderStats();
updateDashboard();

</script>

</body>
</html>
