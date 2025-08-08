<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="A hacking-themed multi-section HTML5 web page with media, tables, lists, and a complete form using built-in validation." />
  <title>Riq's Hacking Hub</title>
</head>

<body>

  <header>
    <h1>Welcome to Riq's Hacking Hub</h1>
    <p>This page showcases HTML5 features using hacking-themed examples: lists, tables, media, and a secure form.</p>
  </header>

  <main>

    <!-- Section: Lists -->
    <section>
      <h2>My Top 3 Hacking Tools</h2>
      <ul>
        <li>Wireshark</li>
        <li>Burp Suite</li>
        <li>Metasploit</li>
      </ul>
    </section>

    <!-- Section: Tables -->
    <section>
      <h2>Weekly Hacking Practice Schedule</h2>
      <table border="1">
        <tr>
          <th>Day</th>
          <th>Focus Area</th>
          <th>Hours</th>
        </tr>
        <tr>
          <td>Monday</td>
          <td>Network Scanning (Nmap)</td>
          <td>2</td>
        </tr>
        <tr>
          <td>Tuesday</td>
          <td>Web Exploits (Burp Suite)</td>
          <td>3</td>
        </tr>
        <tr>
          <td>Wednesday</td>
          <td>Password Cracking (John the Ripper)</td>
          <td>2</td>
        </tr>
      </table>
    </section>

    <!-- Section: Media -->
    <section>
      <h2>Hacker's Inspiration</h2>
      <img src="https://via.placeholder.com/300x150" alt="Hacking in action" />
      <br /><br />
      <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </section>

    <!-- Section: Form -->
    <section>
      <h2>Join the Ethical Hacker Club</h2>
      <form action="#" method="post" autocomplete="on">

        <fieldset>
          <legend>Personal Info</legend>
          <label for="fullname">Full Name:</label><br />
          <input type="text" id="fullname" name="fullname" placeholder="Your name" required minlength="3" /><br /><br />

          <label for="email">Email:</label><br />
          <input type="email" id="email" name="email" placeholder="you@example.com" required /><br /><br />

          <label for="age">Age:</label><br />
          <input type="number" id="age" name="age" min="13" max="100" required /><br /><br />

          <label for="handle">Hacker Alias (no spaces):</label><br />
          <input type="text" id="handle" name="handle" pattern="^\S+$" title="No spaces allowed" required /><br /><br />
        </fieldset>

        <fieldset>
          <legend>Account Setup</legend>
          <label for="password">Password:</label><br />
          <input type="password" id="password" name="password" required minlength="6" /><br /><br />

          <label for="confirm">Confirm Password:</label><br />
          <input type="password" id="confirm" name="confirm" required minlength="6" /><br /><br />

          <label for="region">Select Region:</label><br />
          <select id="region" name="region" required>
            <option value="">--Select--</option>
            <option value="africa">Africa</option>
            <option value="europe">Europe</option>
            <option value="asia">Asia</option>
          </select><br /><br />

          <label>Experience Level:</label><br />
          <input type="radio" name="experience" value="beginner" required /> Beginner
          <input type="radio" name="experience" value="intermediate" required /> Intermediate
          <input type="radio" name="experience" value="pro" required /> Pro<br /><br />
        </fieldset>

        <fieldset>
          <legend>Why Hacking?</legend>
          <label for="bio">Your reason for joining:</label><br />
          <textarea id="bio" name="bio" rows="4" cols="50" placeholder="I'm passionate about cybersecurity because..." required></textarea><br /><br />

          <input type="checkbox" id="terms" name="terms" required />
          <label for="terms">I agree to follow ethical hacking practices</label><br /><br />
        </fieldset>

        <button type="submit">Join the Club</button>

      </form>
    </section>

  </main>

  <footer>
    <p>&copy; 2025 Riq's Ethical Hacking Hub</p>
  </footer>

</body>
</html>
