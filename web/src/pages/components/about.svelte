<!-- About.svelte -->
<script>
    let projectTitle = "ProspectPath: Guiding Your Journey to Academic and Career Success";
    let projectDescription = "ProspectPath is a user-friendly educational website designed to empower students, providing them with a roadmap to academic and career success. We are committed to helping students make informed decisions about their education and future by offering a comprehensive platform filled with interactive tools and a supportive community.";
  
    let projectGoals = [
      "To guide students through their academic and career paths with a structured curriculum tree.",
      "To provide personalized recommendations, career quizzes, and resource suggestions.",
      "To foster a supportive community where students can interact, ask questions, and seek advice from peers and mentors.",
      "To keep the content updated with the latest trends in education and career paths, ensuring relevance.",
      "To prioritize user data security and comply with privacy regulations.",
      "To create a scalable platform that can accommodate a growing user base."
    ];
  </script>
  
  <main class="p-4">
    <div class="bg-gradient-to-b from-blue-500 to-blue-300 py-16 text-white text-center">
      <h1 class="text-4xl font-semibold mb-4">{projectTitle}</h1>
      <p class="text-lg max-w-2xl mx-auto leading-7">{projectDescription}</p>
    </div>
  
    <div class="p-4">
      <h2 class="text-3xl font-semibold mb-4">Our Goals</h2>
      <ul class="list-disc ml-8">
        {#each projectGoals as goal (goal)}
          <li class="text-lg mb-2">{goal}</li>
        {/each}
      </ul>
    </div>
  </main>
  