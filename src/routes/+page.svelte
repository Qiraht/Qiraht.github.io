<script lang="ts">
  import './layout.css';    
</script>

<main id="home">
    <!--- Hero --->
    <section class="text-gray-600 body-font">
    <div class="container mx-auto flex px-5 py-24 items-center justify-center flex-col">
      <img class="lg:w-2/6 md:w-3/6 w-5/6 mb-10 object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600">
        <div class="text-center lg:w-2/3 w-full">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Thariq Aulia Akbar</h1>
        <p class="mb-8 leading-relaxed">Backend Developer based in Indonesia</p>
        <div class="flex  flex-wrap justify-center">
            <a class="m-2 px-4" href="https://www.linkedin.com/in/qiraht/ " target="_blank" rel="noopener noreferrer">
            <img class="align-left size-12" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" alt="LinkedIn">
            </a>
            <a class="m-2 px-4" href="https://github.com/Qiraht " target="_blank" rel="noopener noreferrer">
            <img class="align-left size-12" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" alt="GitHub">
            </a>
            <a class="m-2 px-4" href="https://gitlab.com/qiraht246/" target="_blank" rel="noopener noreferrer">
            <img class="align-left size-12" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gitlab.svg" alt="GitLab">
            </a>
        </div>
        </div>
    </div>
    </section>

    <!-- About -->
    <section id="about" class="text-gray-600 body-font">
      <div class="container mx-auto flex px-5 py-24 items-center justify-center flex-col">
        <div class="text-center lg:w-2/3 w-full">
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">About Me</h1>
          <p class="mb-8 leading-relaxed">
            I'm a passionate backend developer with experience in building web applications using modern technologies. 
            I enjoy solving complex problems and creating intuitive user experiences.
          </p>
          <p class="mb-8 leading-relaxed">
            When I'm not coding, I love exploring new technologies, reading tech blogs, and contributing to open-source projects.
          </p>
          <div class="h-1 bg-gray-200 rounded overflow-hidden">
        <div class="w-24 h-full bg-gray-500"></div>
        </div>
        </div>
      </div>
    </section>
    

    <!-- Skills and Tools -->
    <section id="skills" class="text-gray-600 body-font">
      <div class="container mb-12 mx-auto flex px-5 py-20 items-center justify-center flex-col">
        <div class="text-center lg:w-2/3 w-full">
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Skills & Tools</h1>
          <div class="flex flex-wrap justify-center">
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">JavaScript</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">TypeScript</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Express.js</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Tailwind CSS</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Node.js</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Java</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Spring Boot</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Git</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">PostgreSQL</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Redis</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">Docker</span>
            <span class="m-2 px-4 py-2 bg-gray-200 rounded-full">AWS</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="text-gray-900 body-font">
    <div class="container mx-auto flex px-5 py-24 items-center justify-center flex-col">
        <h1 class="text-3xl font-bold mb-8">Projects</h1>
        <div class="flex items-center lg:w-3/5 mx-auto border-b pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
        <div class="sm:w-32 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="sm:w-16 sm:h-16 w-10 h-10" viewBox="0 0 24 24">
            <path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
            </svg>
        </div>
        <div class="grow sm:text-left text-center mt-6 sm:mt-0">
            <h2 class="text-gray-900 text-lg title-font font-medium mb-2">Digital Payment API</h2>
            <p class="leading-relaxed text-base">A RESTful API for Indonesian digital products (Pulsa, PLN, BPJS, etc. ) using JavaScript, Node, Express, Prisma ORM and PostgreSQL.</p>
            <a class="mt-3 text-indigo-500 inline-flex items-center" href="https://gitlab.com/qiraht246/express-digital-payment-api" target="_blank">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
            </a>
        </div>
        </div>
        <div class="flex items-center lg:w-3/5 mx-auto border-b pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
        <div class="grow sm:text-left text-center mt-6 sm:mt-0">
            <h2 class="text-gray-900 text-lg title-font font-medium mb-2">Forum API</h2>
            <p class="leading-relaxed text-base">Backend API for forum discussion platform API developed using NodeJS (Hapi). Designed with Clean Architecture and developed with Test-Driven Development (TDD). Also includes robust testing and deployment workflows with a CI/CD pipeline.</p>
            <a class="mt-3 text-indigo-500 inline-flex items-center" href="https://gitlab.com/qiraht246/forum-api" target="_blank">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
            </a>
        </div>
        <div class="sm:w-32 sm:order-none order-first sm:h-32 h-20 w-20 sm:ml-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="sm:w-16 sm:h-16 w-10 h-10" viewBox="0 0 24 24">
            <circle cx="6" cy="6" r="3"></circle>
            <circle cx="6" cy="18" r="3"></circle>
            <path d="M20 4L8.12 15.88M14.47 14.48L20 20M8.12 8.12L12 12"></path>
            </svg>
        </div>
        </div>
        <div class="flex items-center lg:w-3/5 mx-auto sm:flex-row flex-col">
        <div class="sm:w-32 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="sm:w-16 sm:h-16 w-10 h-10" viewBox="0 0 24 24">
            <path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2"></path>
            <circle cx="12" cy="7" r="4"></circle>
            </svg>
        </div>
        <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
            <h2 class="text-gray-900 text-lg title-font font-medium mb-2">Open Music API</h2>
            <p class="leading-relaxed text-base">Backend API for music repository provider developed using NodeJS, Hapi, Postgres, Redis, Nodemailer, and RabbitMQ.</p>
            <a class="mt-3 text-indigo-500 inline-flex items-center" href="https://gitlab.com/qiraht246/open-music-api" target="_blank">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
            </a>
        </div>
        </div>
      </div>
    </section>

    <section id="contact" class="text-gray-600 body-font">
  <div class="container mx-auto flex px-5 py-24 items-center justify-center flex-col">
    <img class="lg:w-2/6 md:w-3/6 w-5/6 mb-10 object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600">
    <div class="text-center lg:w-2/3 w-full">
      <h1 class="title-font sm:text-4xl text-3xl mb-2 font-medium text-gray-900">Lets Connect</h1>
      <p class="mb-2 leading-relaxed">
        Feel free to reach out for collaborations or just a friendly hello!
      </p>
      <a class="leading-relaxed hover:text-gray-900 hover:underline" href="mailto:thariq@2712@gmail.com" target="_blank" rel="noopener noreferrer">email</a>
      <a class="leading-relaxed hover:text-gray-900 hover:underline" href="https://www.linkedin.com/in/qiraht" target="_blank" rel="noopener noreferrer">linkedin</a>
    </div>
  </div>
</section>
</main>