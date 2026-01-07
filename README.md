Add conetent like this
-----
in index.html

 use this to add new posts
 ---------------------
        const posts = [
            { id: 0, title: 'The New Era 2026', src: 'TheNewEra2026.html', category: 'InterLink Labs' },
            { id: 1, title: '2025 - Achievements', src: '2025Achievements.html', category: 'InterLink Labs' }
        ];

Use below to change site content
------------
if (headerHome) headerHome.addEventListener('click', (e) => { e.preventDefault(); contentFrame.src = 'Code base/index1.html'; activeId = null; renderNavigation(posts); setHeaderActive('home'); });
        if (headerAbout) headerAbout.addEventListener('click', (e) => { e.preventDefault(); contentFrame.src = 'Code base/BaseTemplate.html'; activeId = null; renderNavigation(posts); setHeaderActive('about'); });
        if (headerEvents) headerEvents.addEventListener('click', (e) => { e.preventDefault(); contentFrame.src = 'Code base/events.html'; activeId = null; renderNavigation(posts); setHeaderActive('events'); });
