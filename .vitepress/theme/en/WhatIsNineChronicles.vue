<template>
    <div class="what-is-nine-chronicles">
        <div class="content">
            <div class="image-container">
                <img src="/ninechronicles.jpeg" alt="Nine Chronicles Game" class="game-image" />
            </div>
            <div class="text-container">
                <div class="title">What Is Nine Chronicles?</div>
                <div class="description">
                    <a href="https://docs.nine-chronicles.com/introduction" target="_blank" class="highlight">Nine
                        Chronicles</a> is a fully open-sourced online RPG<br />
                    Set in a vast fantasy world, it operates on a distributed game network powered by gamers.<br />
                    <b>every action in the Nine Chronicles ecosystem is recorded on the blockchain</b>, ensuring
                    transparency and security.
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.what-is-nine-chronicles {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 120px;
    padding: 0 20px;
}

.content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 60px;
    word-break: keep-all;
    flex-wrap: wrap;
}

.image-container {
    flex: 1;
    max-width: 500px;
}

.game-image {
    width: 100%;
    height: auto;
    aspect-ratio: 3 / 2;
    object-fit: cover;
    border-radius: 15px;
}

.text-container {
    flex: 1;
}

.title {
    font-size: 40px;
    margin-bottom: 1rem;
    font-weight: 600;
    line-height: 2.5rem;
}

.description {
    font-size: 20px;
    line-height: 32px;
    margin-bottom: 1rem;
}

a.highlight {
    color: #b81d82;
    text-decoration: none;
}

a.highlight:hover {
    text-decoration: underline;
}

@media (max-width: 768px) {
    .content {
        flex-direction: column;
        gap: 30px;
    }

    .title {
        font-size: 32px;
    }

    .description {
        font-size: 18px;
        line-height: 28px;
    }
}

@media (max-width: 480px) {
    .title {
        font-size: 28px;
    }

    .description {
        font-size: 16px;
        line-height: 24px;
    }
}
</style>