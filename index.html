<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Study Group Feedback</title>
  <style>
    :root {
      --accent: #6C63FF;
      --accent2: #FF6B6B;
      --muted: #6b7280;
      font-family: Inter, sans-serif;
    }
    html, body { margin:0; padding:0; height:100%; }
    .page { display:none; min-height:100vh; width:100%; }
    .active { display:flex; }
    /* Welcome Page */
    #welcome {
      flex-direction:column; align-items:center; justify-content:center;
      background:linear-gradient(135deg,#6C63FF,#FF6B6B);
      color:white; text-align:center; padding:20px;
    }
    #welcome h1 { font-size:2rem; margin-bottom:10px; }
    #welcome p { font-size:1.1rem; max-width:500px; margin:0 auto 20px; }
    #welcome button {
      background:white; color:#6C63FF; padding:12px 24px;
      font-size:1rem; border:none; border-radius:8px;
      cursor:pointer; font-weight:bold;
    }
    #welcome button:hover { background:#f1f1f1; }
    /* Form Page */
    #formPage {
      flex-direction:column; align-items:center;
      background: radial-gradient(circle at top left, rgba(108,99,255,0.2), transparent 40%),
                  radial-gradient(circle at bottom right, rgba(255,107,107,0.2), transparent 40%),
                  linear-gradient(135deg,#0f172a,#081226,#02121a);
      color:#0b1220; padding:20px;
    }
    .form-container {
      background:white; border-radius:12px; padding:20px;
      max-width:800px; width:100%; box-shadow:0 8px 24px rgba(0,0,0,0.2);
    }
    h2 { margin-top:0; }
    label { display:block; font-size:14px; margin:10px 0 4px; color:var(--muted); }
    input, textarea, select {
      width:100%; padding:10px; border:1px solid #ddd;
      border-radius:6px; margin-bottom:8px; font-size:14px;
    }
    .rating { display:flex; gap:10px; margin-bottom:10px; }
    button.primary {
      background:linear-gradient(90deg,var(--accent),var(--accent2));
      border:none; color:white; padding:10px 20px;
      border-radius:8px; font-weight:bold; cursor:pointer;
    }
    button.primary:hover { opacity:0.9; }
  </style>
</head>
<body>
  <!-- Page 1: Welcome -->
  <div id="welcome" class="page active">
    <h1>Welcome to the Study Group Feedback</h1>
    <p>We value your opinion! Click below to proceed and share your honest feedback with us. Your responses are anonymous unless you choose otherwise.</p>
    <button id="proceedBtn">Click to Proceed</button>
  </div>

  <!-- Page 2: Form -->
  <div id="formPage" class="page">
    <div class="form-container">
      <h2>Feedback Form</h2>
      <form id="evaluationForm">
        <label for="name">Name (optional)</label>
        <input type="text" id="name" name="name" placeholder="Your name">

        <label for="likes">What did you like most about the study group?</label>
        <textarea id="likes" name="likes"></textarea>

        <label for="challenges">Did you face any challenges?</label>
        <textarea id="challenges" name="challenges"></textarea>

        <label for="improvements">What should we improve?</label>
        <textarea id="improvements" name="improvements"></textarea>

        <label>Rate the overall study group performance (1–5)</label>
        <div class="rating">
          <label><input type="radio" name="performance" value="1">1</label>
          <label><input type="radio" name="performance" value="2">2</label>
          <label><input type="radio" name="performance" value="3">3</label>
          <label><input type="radio" name="performance" value="4">4</label>
          <label><input type="radio" name="performance" value="5" checked>5</label>
        </div>

        <label>Was anyone annoying in the study group?</label>
        <select name="annoying">
          <option value="No">No</option>
          <option value="Yes">Yes</option>
        </select>

        <label for="annoying_person">If yes, who/what was annoying?</label>
        <textarea id="annoying_person" name="annoying_person"></textarea>

        <label for="takeaway">What key lesson or insight will you take away?</label>
        <textarea id="takeaway" name="takeaway"></textarea>

        <label for="recommend">Would you recommend this study group to others? Why/why not?</label>
        <textarea id="recommend" name="recommend"></textarea>

        <button type="submit" class="primary">Submit</button>
      </form>
    </div>
  </div>

  <script>
    // Navigation
    document.getElementById("proceedBtn").addEventListener("click", () => {
      document.getElementById("welcome").classList.remove("active");
      document.getElementById("formPage").classList.add("active");
    });

    // Replace with your Apps Script URL
    const webAppUrl = "YOUR_WEB_APP_URL_HERE";

    document.getElementById("evaluationForm").addEventListener("submit", async (e) => {
      e.preventDefault();
      const fd = new FormData(e.target);
      const data = {};
      fd.forEach((v, k) => data[k] = v);

      try {
        const res = await fetch(webAppUrl, {
          method: "POST",
          headers: { "Content-Type": "application/json" },
          body: JSON.stringify(data)
        });
        if (res.ok) {
          alert("✅ Thank you! Your response was recorded.");
          e.target.reset();
        } else {
          alert("❌ Something went wrong.");
        }
      } catch (err) {
        alert("⚠️ Error: " + err.message);
      }
    });
  </script>
</body>
</html>
