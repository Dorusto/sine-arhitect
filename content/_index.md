---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Simți că ești străin chiar și în viața ta?
      text: Coaching 1-la-1, cu cineva care a simțit asta… și a învățat să se regăsească.
      primary_action:
        text: 📅 Programează o sesiune
        url: https://calendly.com/dorulian/45min
        icon: rocket-launch
      #secondary_action:
      #  text: 📨 Trimite-mi un mesaj
      #  url: https://docs.hugoblox.com
      announcement:
        text: "📖 Povestea mea."
        link:
          text: "Citește"
          url: "/#povestea-mea"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: doru.JPEG
          filters:
            brightness: 0.5
  #- block: stats
  #  content:
  #    items:
  #      - statistic: "1M+"
  #        description: |
  #          Websites built  
  #          with Hugo Blox
  #      - statistic: "10k+"
  #        description: |
  #          GitHub stars  
  #         since 2016
  #      - statistic: "3k+"
  #        description: |
  #          Discord community  
  #          for support
  #  design:
      # Section background color (CSS class)
  #    css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
  #    spacing:
  #      padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: povestea-mea
    content:
      items:
        - title: 📖 De unde am plecat
          text: Un copil mediu la școală, ba chiar cu probleme. Anxietatea față de școală și profesori, combinată cu gândul că nu sunt suficient de capabil, mi-au creat mari probleme. Cu toate astea, eram un puști inventiv și descurcăreț. Am făcut bani din muncă pe câmp până la făcut decodoare TV pe  când HBO era bruiat. Am fost operator într-o sală de internet, apoi electrician pe șantier. Am făcut armata, dar m-am întors mai fragil decât am plecat. A urmat o perioadă de muncă ca electrician chiar și în SUA. Munca de jos m-a împins să urmez o facultate și apoi un master în automatizări. Am lucrat în fotografie și film și chiar am câștigat locul I la un festival de arte vizuale. În final, mi-am îndeplinit visul de a lucra ca automatist. Totuși, nu mi-am dat niciodată meritul. Mă simțeam insuficient. Burnoutul a fost inevitabil, dar a fost și începutul unei transformări.
          feature_icon: book-open
          features:
            - "Inventiv și descurcăreț încă din copilărie"
            - "Experiență variată: operator, electrician, automatist"
            - "Burnoutul reprezintă începutul unei noi direcții"
          # Upload image to `assets/media/` and reference the filename here
          image: copil.png
          button:
            text: 📅 Programează o sesiune
            url: https://calendly.com/dorulian/45min
        - title: 🌱 Unde sunt acum
          text: Gândul că nu știam ce vreau de la viață mă paraliza. Simțeam că timpul trece și eu nu aparțin nicăieri. Eram tot timpul trist, mimam că e ok, dar nu era. Am ajuns să amân somnul doar ca să evit o nouă zi. Nu găseam sens în nimic. Dar apoi… am început să caut. Să mă ascult. Să înțeleg. Astăzi, nu sunt perfect și nici nu vreau să fiu. Însă știu cine sunt, ce vreau, ce merit. Am învățat să-mi accept vulnerabilitățile și să le transform în puncte de sprijin. Am înțeles că nu sunt singurul și, mai ales, că nici tu nu ești.
          feature_icon: sparkles
          features:
            - "Autocunoaștere și acceptare autentică"
            - "Transformarea vulnerabilităților în putere"
            - "Ghidare pentru alții aflați în căutare"
          # Upload image to `assets/media/` and reference the filename here
          image: adult.png
          button:
            text: 📅 Programează o sesiune
            url: https://calendly.com/dorulian/45min
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: features
    id: coaching
    content:
      title: Coaching 1 la 1
      text: "Uneori, tot ce avem nevoie este un spațiu sigur în care să fim ascultați cu adevărat.  
      Coachingul 1 la 1 este o conversație profundă, ghidată cu empatie și claritate, în care tu ești în centrul atenției.  
      Împreună, lucrăm pentru a înțelege ce te ține pe loc, pentru a descoperi ce îți dorești cu adevărat și pentru a crea pași concreți spre o versiune mai autentică și împlinită a ta."
      button:
        text: 📅 Programează o sesiune
        url: https://calendly.com/dorulian/45min
      items:
        - name: Înțelegerea frământărilor
          icon: question-mark-circle
          description: Explorăm împreună provocările tale interioare pentru a înțelege ce te apasă cu adevărat.
        - name: Clarificarea dorințelor
          icon: heart
          description: Identificăm ce îți dorești cu adevărat și ce te face cu adevărat fericit.
        - name: Definirea obiectivelor
          icon: flag
          description: Stabilim împreună obiective clare și realizabile, adaptate nevoilor tale.
        - name: Găsirea soluțiilor
          icon: light-bulb
          description: Lucrăm împreună pentru a descoperi soluții practice și eficiente la problemele tale.
        - name: Claritate și încredere
          icon: eye
          description: Te ajut să recapeți claritatea mentală și încrederea în propriile forțe.
        - name: Suport continuu
          icon: user-group
          description: Îți ofer sprijin constant pe parcursul procesului de transformare personală.
  - block: features
    id: valori
    content:
      title: Valorile mele
      text: Aceste valori nu sunt doar cuvinte pentru mine - ele ghidează fiecare interacțiune și fiecare sesiune de coaching. Ele reprezintă fundația pe care construim împreună relația de încredere necesară pentru o transformare autentică.
      items:
        - name: Sinceritate
          icon: chat-bubble-left-right
          description: Creăm împreună un spațiu sigur unde poți fi tu însuți, fără mască și fără judecăți. Fiecare cuvânt contează și fiecare emoție este validă. 
        - name: Respect
          icon: users
          description: Fiecare persoană are propria poveste și propriul ritm. Respect timpul tău, experiențele tale și drumul tău unic, fără a încerca să-l accelerez  sau să-l schimb.
        - name: Egalitate
          icon: scale
          description: Voi fi partenerul tău în călătoria ta. Lucrez împreună cu tine pentru a descoperi problema dar și soluția cea mai bună pentru tine.
        - name: Empatie
          icon: heart
          description: Înțelegerea profundă a experiențelor tale și a emoțiilor tale este esențială. Sunt aici să te ascult și să te susțin, fără să judec.
        - name: Adevăr
          icon: magnifying-glass
          description: Căutăm împreună adevărul tău interior. Uneori, acest proces poate fi incomod, dar este necesar pentru creștere și transformarea ta autentică.
        - name: Autenticitate
          icon: sparkles
          description: Cred în puterea de a fi tu însuți, fără mască și fără compromisuri. În coaching, autenticitatea este cheia pentru o transformare durabilă și împlinitoare.
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    id: testimoniale
    content:
      title: ""
      text: ""
      items:
        - name: "Andreea, 34 ani"
          role: "Project manager"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: Sesiunile de coaching cu Doru au fost revelatoare. Am reușit să mă reconectez cu mine însumi și să-mi clarific direcția în viață. M-am simțit ascultat, înțeles și sprijinit la fiecare pas. Recomand din inimă!
        - name: "Andrei, 34 ani"
          role: "Arhitect"
          image: "testimonial-1.jpg"
          text: Sesiunile de coaching cu Doru au fost revelatoare. Am reușit să mă reconectez cu mine însumi și să-mi clarific direcția în viață. M-am simțit ascultat, înțeles și sprijinit la fiecare pas. Recomand din inimă!
    design:
      # css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    id: cta
    content:
      title: Te invit la o discuție deschisă
      text: O discuție sinceră poate fi primul pas spre claritate
      button:
        text: 📅 Programează o sesiune
        url: https://calendly.com/dorulian/45min
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-gray-800"
        css_style: "bg-gray-100 dark:bg-gray-900"
---
