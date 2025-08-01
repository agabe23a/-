<div class="topic-box">
  <h2>Learn Python</h2>
  <p id="summary">
    Python is a beginner-friendly programming language known for its readability and flexibility...
    <span id="dots">...</span>
    <span id="more" style="display: none;">
      It is used in web development, data science, automation, AI, and more. You can start with basic syntax, variables, loops, then move to frameworks like Flask or Django.
    </span>
  </p>
  <button onclick="toggleReadMore()" id="readBtn">Read More</button>
</div>

<script>
  function toggleReadMore() {
    const dots = document.getElementById("dots");
    const moreText = document.getElementById("more");
    const btnText = document.getElementById("readBtn");

    if (dots.style.display === "none") {
      dots.style.display = "inline";
      moreText.style.display = "none";
      btnText.innerText = "Read More";
    } else {
      dots.style.display = "none";
      moreText.style.display = "inline";
      btnText.innerText = "Read Less";
    }
  }
</script>
