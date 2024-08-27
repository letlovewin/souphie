<script>
    import "../app.css";
</script>

<svelte:head>
    <title>gray's tutoring</title>
</svelte:head>

<div class="container main-container mt-2">
    <div class="row">
        <div class="col d-flex align-items-center justify-content-center">
            <img
                class="rounded mt-5"
                src={"/souphie.jpg"}
                alt="Souphie logo"
                style="height:330px;max-width:330px;"
            />
        </div>
        <div class="col">
            <h1><strong>gray's tutoring</strong></h1>
            <p>i'm a tutor with a focus on mathematics and computer science.</p>
            <p>currently i offer</p>
            <ul>
                <li>algebra I & II</li>
                <li>geometry & trigonometry</li>
                <li>precalculus</li>
                <li>calculus I & II</li>
                <li>ap statistics</li>
                <li>discrete mathematics</li>
                <li>data structures & algorithms</li>
                <li>ap english language & composition</li>
                <li>ap us history</li>
                <li>ap european history</li>
                <li>ap human geography</li>
                <li>ap us government & politics</li>
            </ul>
            <p>
                in all of these classes, i've gotten at least an A and/or a 4 on
                the exam for the class.
            </p>
            <p>
                these are all offered at a rate of $25/hour. to make an
                appointment please DM me on <a
                    href="https://instagram.com/graythedye">instagram</a
                >.
            </p>
        </div>
    </div>
    <div class="row">
        <div class="text-center pt-2">
            <a href="mailto:graythecolor@proton.me">email</a> /
            <a href="https://instagram.com/graythedye">instagram</a>
        </div>
    </div>
</div>
