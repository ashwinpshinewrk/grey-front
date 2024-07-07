<script>
    const rules = [
        "First of all, love the Lord God with your whole heart, your whole soul, and your whole strength. ",
        "Then, love your neighbor as yourself. ",
        "Do not muder.",
        "Do not commit adultery",
        "Do not steal",
        "Do not covet",
        "Do not bear false witness",
        "Honor all people",
        "Do not do to another what you would not have done to yourself",
        "Chastise the body",
        "Do not become attached to pleasures",
        "Love to fast",
        "Relieve the poor",
        "Clothe the naked",
        "Visit the sick",
        "Bury the dead",
        "Be a help in times of trouble",
        "Console the sorrowing",
        "Be a stranger to the world's ways",
        "Do not give way to anger",
        "Do not nurse a grudge.",
        "Do not entertain deceit in your heart.",
        "Do not give a false peace.",
        "Do not forsake charity.",
        "Do not swear, for fear of perjuring yourself.",
        "Utter only truth from heart and mouth.",
        "Do not return evil for evil. ",
        "Do no wrong to anyone, and bear patiently wrongs done to yourself.",
        "Love your enemies.",
        "Be not lazy.",
        "Be not a gambler",
        "Put your hope on God",
        "Disclose wrongful thoughts to your spiritual mentor.",
        "Guard your tongue against evil and depraved speech.",
        " Respect your seniors.",
        "Love your juniors. ",
    ];

    const prules = [
        "Use Rust standard variabel naming",
        "Always defer the free next to allocation",
        "Communicate with intent (Use comment only when needed, let your variable names speak",
        "Edge case matters",
        "Small improvements overtime",
        "Let it crash for us, so user can run it",
        "Anything and everything can fail.",
        "Memory is a resource",
        "I dont know webdev",
    ];
</script>

<h1>Rules on programming</h1>
<ol>
    {#each prules as r}
        <li>{r}</li>
    {/each}
</ol>

<h1>Rules on life</h1>
<ol>
    {#each rules as rule}
        <li>{rule}</li>
    {/each}
</ol>

<a href="/portfolio/ashwin">Go Back</a>