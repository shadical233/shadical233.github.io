<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ASF Special Forces</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="background"></div>
  <div class="content-box">
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#units">Units</a></li>
        <li><a href="#chain">Chain of Command</a></li>
        <li><a href="#join">How to Join</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <section id="home">
      <h1>ASF Special Forces</h1>
      <p>Welcome to the official site for ASF's elite Special Forces groups.</p>
    </section>

    <section id="units">
      <h2>1st Special Forces Group</h2>
      <p>The First Special Forces Group has two companies, Alpha and Bravo. Alpha Company focuses on First Person Shooters such as Tournament Grounds and Raid Grounds. Bravo Company focuses on War Games. The First Special Forces Group is the main combat force of ASF.</p>

      <h2>10th Special Forces Group</h2>
      <p>The 10th Special Forces Group has two companies, Whiskey and Yankee. Whiskey Company focuses on First Person Shooters while training the Alpha Company. Yankee Company focuses on War Games while training the Bravo Company. The 10th Special Forces Group is a Training and Recruitment Special Forces Group for ASF. However, they are actively participating in operations.</p>

      <h2>Task Force 121</h2>
      <p>Task Force Operator specialized in MILSIM, which stands for Military Simulation. MILSIM defines when elite operations are realistic and similar to what might be seen in a real-life scenario. Task Force 121 goes on various MILSIM deployments with other divisions and groups.</p>
    </section>

    <section id="chain">
      <h2>Chain of Command</h2>
<h3>1st Special Forces Group</h3>
      <ul>
        <li>Group Commanding Officer: [Name]</li>
        <li>Group Executive Officer: [Name]</li>
        <li>Group First Sergeant: [Name]</li>
        <li>Alpha Company: CCO, CXO, C1SG</li>
        <li>Bravo Company: CCO, CXO, C1SG</li>
      </ul>

      <h3>10th Special Forces Group</h3>
      <ul>
        <li>Group Commanding Officer: [Name]</li>
        <li>Group Executive Officer: [Name]</li>
        <li>Group First Sergeant: [Name]</li>
        <li>Whiskey Company: CCO, CXO, C1SG</li>
        <li>Yankee Company: CCO, CXO, C1SG</li>
      </ul>

      <h3>Task Force 121</h3>
      <ul>
        <li>Group Commanding Officer: [Name]</li>
        <li>Group Executive Officer: [Name]</li>
        <li>Group First Sergeant: [Name]</li>
        <li>Neptune Company: CCO, CXO, C1SG</li>
        <li>Jaeger Company: CCO, CXO, C1SG</li>
      </ul>
    </section>

    <section id="join">
      <h2>How to Join</h2>
      <p>To become a part of ASF Special Forces, you must meet the requirements and pass a tryout. Contact a recruiter or visit our Discord to get started.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Discord: [Your Discord Link]<br>Roblox Group: [Your Roblox Group Link]</p>
    </section>
  </div>
</body>
</html>

/* Background image & layout /
body, html {
  margin: 0;
  padding: 0;
  height: 100%;
  font-family: Arial, sans-serif;
  background-color: #000;
  color: #ccc;
}

.background {
  background-image: url('https://i.imgur.com/9Z1Zoj4.jpg'); /(https://cdn.discordapp.com/attachments/1152681587922702517/1361032044578344970/deoppressoliberhostagerescue121.png?ex=680bc7de&is=680a765e&hm=c24f2ee128d0ad45eb4b0fab858b6e2ca26d898b4b9ee9b3f6c2bbfe0cb514ab&)*/
  background-size: cover;
  background-position: center;
  position: fixed;
  width: 100%;
  height: 100%;
  z-index: -1;
  filter: brightness(0.4);
}

.content-box {
  background-color: rgba(20, 20, 20, 0.95);
  max-width: 800px;
  margin: 50px auto;
  padding: 30px;
  border-radius: 10px;
  overflow-y: auto;
  max-height: 90vh;
  box-shadow: 0 0 20px rgba(0, 255, 0, 0.2);
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
  justify-content: center;
  margin-bottom: 20px;
}

nav a {
  text-decoration: none;
  color: #8f8;
  font-weight: bold;
  padding: 8px 12px;
  border: 1px solid #4a4;
  border-radius: 5px;
  transition: background 0.3s;
}

nav a:hover {
  background-color: #2d2;
  color: #000;
}

h1, h2, h3 {
  color: #8f8;
  margin-top: 20px;
}

section {
  margin-bottom: 30px;
}

ul {
  padding-left: 20px;
}
