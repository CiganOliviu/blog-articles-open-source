# 8 Rules of Software Engineers

Embarking on my journey in the Software Development industry began in high school, where I delved into various technologies and coding practices. By the time I entered university, I had a solid foundation in good coding practices, understood RESTful API architecture, comprehended MVC principles, and was acquainted with diverse programming paradigms. This laid a strong groundwork, marking me as a well-defined junior in the field.

However, the reality check arrived during my first internship. It was a crash course in the gaps between theoretical knowledge and practical application. Concepts that seemed concrete in theory became fluid and nuanced in practice. Each day was a lesson, revealing the intricacies and subtleties of how systems truly operate.

As I transitioned into a Software Engineer role after receiving and accepting a job offer, the realization dawned that my learning had only just begun. Despite the immense growth during the internship, it was merely scratching the surface. After only a few days onboarding, I jumped into a real world project with an enterprise client, a huge television operator from central Europe.

I’ve gathered a wealth of invaluable lessons from firsthand experiences, whether through my own trials, observing others’ mistakes, or receiving insightful feedback. Some of these experiences have been distilled into the following set of golden rules:

### 1. Fundamentals is key.

Once, at a conference in Cluj-Napoca, I believe it was 2018, there was an eye-opening presentation titled “Job vs Career” (or something like that) that left a lasting impression on me. While I can’t recall every detail of the discussion, the opening slide remains vivid in my memory: “Learn a framework to obtain a job and learn your fundamentals to build a career.”

It’s tempting to fall into the trap of mastering a framework solely because a job demands it. Yet, entry-level individuals often overlook a crucial reality — frameworks are transient. They emerge, thrive, and eventually fade away. Some enduring frameworks like Spring, .NET, Django, and Laravel have stood the test of time. However, the concern extends beyond the mortality of frameworks.

Frameworks frequently abstract intricate logic, obscuring the core methodology and functionality. This abstraction can be a boon for experienced professionals, alleviating concerns about security, code architecture, or even the implementation of design patterns. However, for those with limited experience, lacking a grasp of fundamental software design concepts, this abstraction can pose significant challenges.

Let me clarify — I, too, ventured into learning Django early in my journey. However, it was a parallel endeavor to my exploration of software design fundamentals. The goal wasn’t merely to grasp Django for the sake of it; it was to comprehend the underlying mechanisms of Django as a framework. As my understanding deepened, I even developed my own mini-web-framework in PHP.

When we talk about the Fundamentals of Software Design, it’s a wide spectrum. It encompasses grasping basic concepts like control flow, conditionals, and loops, diving into optimization techniques, understanding programming paradigms, and extending to the realm of Software Architecture Design and Design Patterns.

The point I want to stress is not to delay learning a framework until you’ve mastered every single design pattern, architecture, and programming paradigm. However, it’s crucial not to fall into the trap of assuming that knowing a specific framework equates to understanding these fundamentals.

It’s about finding a balance. While learning a framework, make time to practice Test-Driven Development (TDD), explore different Design Patterns, and delve into various Software Architectures. These aspects are the compass points steering one towards a successful career in software development. They shape a more comprehensive understanding of the craft and ultimately pave the way for a successful software career.

Even though at the time I wasn’t working as a professional Software Developer, and thus wasn’t truly aware of all these things, now, after spending some time in the professional field, I can recall, remember, and thereby reinforce a thought I’ve always had since that day.

Fundamentals is they key.

### 2. Be technology agnostic.

This principle stems from the first one: it’s crucial to grasp that you’re not solely a Java Engineer, a .NET Engineer, a Python Engineer, or a JS Engineer — you’re a Software Engineer.

A Software Engineer’s role involves analyzing the project at hand and, based on its requirements, needs, and future development direction, selecting the most suitable technology.

Consider this example: A client needs a mobile app for both iOS and Android that isn’t heavily resource-intensive, reasonably compact in scale, and doesn’t demand intensive processing. Opting for a hybrid approach makes sense here. Using a single technology for both platforms streamlines maintenance, eases development, and minimizes expenditure from a business perspective. Simplicity is key, and in this scenario, choosing a hybrid tech simplifies the solution.

Now, let’s say you’re unfamiliar with hybrid tech. Given your grasp of fundamentals, how Software operates, and Software Design, diving into a new tech stack shouldn’t be daunting. In a matter of weeks — much like my experience — you’d likely become productive with it. When I started my internship and was introduced to React, though I understood its concept, I hadn’t developed anything using it. The initial week was challenging, the second brought understanding and basic implementation, and by the third, React felt comfortable. Surprisingly, within two months, despite being a junior, I was assigned to an enterprise project built with React.

If I managed this, so can you. The point is, let the benefits a technology brings to the final product drive your decision-making, not solely your familiarity with it.

### 3. Consider the market.

Choosing the right technology is paramount when securing a software development role. It’s crucial to align your skill set with the prevalent programming languages in your region. For instance, if Python Django lacks job opportunities compared to the high demand for PHP roles, investing solely in Python Django might not be the wisest choice.

However, while learning a new framework is always beneficial, maximizing your job prospects involves readiness in the sought-after tech stack. Companies typically recruit based on specific technology requirements for current projects. They prioritize candidates who can seamlessly integrate into the team and contribute immediately, without extensive training periods, specifically in the current economic conditions.

Especially for mid-senior positions, it’s not just about being comfortable with the stack; it’s about thriving within it. Companies seek individuals who not only possess proficiency but thrive in their chosen tech stack.

Striking a balance between exploring new frameworks and meeting job market demands is essential. Keeping abreast of tech trends, understanding local job market needs, and continuously enhancing your skills can provide the competitive advantage necessary to navigate the dynamic tech industry landscape.

Before diving into the job hunt, conducting thorough research can be a game-changer. Take a closer look at local companies, their tech requirements, and the predominant stacks they use. Tailoring your skill set towards these specific demands can significantly boost your chances of landing a job.

By aligning your expertise with the prevalent tech stacks sought by local companies, you’re optimizing your opportunities. This targeted approach increases the likelihood of being a perfect fit for the roles available in your area. It’s a strategy that enhances your competitiveness and enhances your prospects of securing the job you’re aiming for.

### 4. Avoid the tech noise

Tech noise refers to technologies, whether outdated, fading, or lacking market value. Learning something like BunJs or CoffeScript isn’t beneficial if it doesn’t significantly enhance the current tech stack. One of my mentors often emphasized that for a new technology to replace an existing one, it should offer a substantial improvement, perhaps tenfold. Companies won’t invest in transitioning from, say, Node to BunJs just for a slight speed increase.

Consider the maturity of a tech stack: its community, available resources, and problem-solving capabilities. Mature technology isn’t just about age but also about how well-supported and versatile it is. For instance, when facing issues in Node, solutions are readily available on platforms like Stack Overflow, unlike less established technologies like BunJS, causing potential roadblocks in development.

The comparison between CoffeScript and Typescript underscores the importance of making decisions based on solid reasoning rather than following trends. It’s crucial not to be swayed by the allure of a fancy technology just because it’s the latest hype. Being technology agnostic means avoiding attachment to any particular stack and instead carefully selecting based on well-defined, substantial reasons for initiating development with it.

V1 technologies, while potentially promising, can be precarious for real-world development. They might serve for experimental purposes but often fall into the realm of tech noise — technologies lacking significant market viability or proven reliability.

Establishing a stable technology with an extensive community and thorough documentation demands significant time and persistent dedication. A seasoned Software Engineer prioritizes ensuring the stability of the chosen tech stack for a project.

### 5. Code is crucial

The significance of code quality cannot be overstated. It forms the core of an application, dictating its behavior and functionality. However, in many instances, there’s a tendency to compromise code quality for the sake of speedy delivery. This practice shouldn’t be acceptable, especially for a professional software engineer who comprehends that prioritizing code quality over feature delivery is imperative.

Code stands as the narrative of the software’s development, illustrating how each module behaves. It should be clear and descriptive, comprehensible to programmers of varying experience levels. As one of my mentors used to emphasize, code ought to be so clear that even a cat could understand it. Indeed, clean, meticulously structured, and well-defined code is key.

Consider this: How can a system be extended when it’s entangled in messy dependencies between modules? How can a new engineer decipher poorly structured code filled with inconsistencies in naming conventions, dependencies, spacing, and convoluted logic? The solution to these challenges lies in clean code — code that facilitates extension, comprehension, and maintenance effortlessly.

### 6. Software Architecture is crucial

Distinguishing between architecture and the tech stack is crucial. Architecture refers to how systems communicate, their independent structures, and the patterns used to solve specific problems. On the other hand, the tech stack, like programming languages and frameworks, serves as tools to materialize the architecture but isn’t the architecture itself.

Consider building a house: the architecture represents the structure, where doors are placed, the depth of the foundation, etc. Similarly, in software, the architecture details how the system operates, while programming languages and tools are akin to hammers or vans in construction — they’re the tools employed to bring the architecture to life.

A robust architecture employs established patterns like Hexagonal, Clean, or Domain-Driven Design. The choice of architecture depends on the problem at hand, but its essence lies in shaping the software’s possibilities. It defines the system’s overall behavior once all the interconnected parts are assembled, creating a functional software system.

### 7. Tests, tests and tests

Testing your code consistently and integrating tests into the development process is essential. While many emphasize quality, true assurance often comes from comprehensive testing. This practice, advocated by experienced programmers, has endured for decades because it yields tangible results.

Tests provide numerous benefits:

- They guarantee quality based on evidence, not just claims.

- By minimizing human errors, tests reduce the likelihood of bugs.

- They enhance software reliability, especially during modifications or expansions.

- Tests serve as valuable documentation for new team members.

Although writing quality tests demands time and effort, it’s an investment with long-term rewards. While it may seem time-consuming initially, the hours saved in the future are substantial and near at hand.

The decision to test hinges on your tolerance for bugs. If overlooking occasional production issues isn’t a concern or if you’re unconcerned about the software’s future, tests might not seem necessary. However, for those valuing software longevity, stability, and a bug-free production environment, various automated tests — such as unit, automation, and performance testing — are crucial.

Consider Threat Modeling, which revolves around assessing your bug tolerance. Critical systems like banking or aviation demand rigorous testing due to low tolerance for errors. Conversely, less critical platforms might accept occasional issues in production. Tailoring tests based on this assessment is crucial.

In essence, a software system lacking tests is akin to operating in legacy mode, susceptible to unforeseen issues and vulnerabilities.

### 8. Soft skill

The quote might seem humorous, but it holds a lot of truth. Soft skills are essential for engineers. The ability to collaborate effectively, handle challenges gracefully, maintain composure, mentor colleagues, and translate technical jargon for non-technical individuals are vital skills.

Reflecting on my experience, I’ve realized that a significant portion of time as a software engineer is dedicated to meetings, discussions, and communication. Coding, while crucial, only occupies the other half. In light of this, hiring someone with exceptional technical skills but lacking in interpersonal abilities might lead to obstacles in the long term.

The ideal engineer possesses a balanced proficiency in both hard and soft skills, recognizing the importance of each in ensuring success and productivity in the industry.

Exploring top books on negotiation, psychology, communication, human nature, and self-control is highly recommended to gain a profound understanding of what soft skills truly embody. Personally, I’ve found that comprehending soft skills, like many important concepts, necessitates practice and dedicated learning. Mere commentary without a grasp of the underlying principles often falls short.

Soft skills extend beyond interpersonal interactions — they encompass how you approach code reviews. It’s essential to articulate the reasons behind recommendations, even if they seem apparent. Consistently emphasizing fundamental concepts fosters stability over time. When providing feedback, prioritize meaningful, purposeful comments rather than superficial ones, focusing on impactful aspects. Additionally, understanding when and where to leave a level of originality into others’ code is a key aspect of soft skills in software development.

In conclusion, While this list may seem exhaustive, I’ve found each rule to be invaluable in guiding my decisions within the engineering field. These principles have not only served me well but continue to do so. Many of these concepts are echoed by individuals far more knowledgeable than myself, such as Bob Martin, Kent Beck, Martin Fowler, and others — seasoned engineers who deeply grasp the industry’s workings and its future trajectory.

Each rule is succinctly described, offering an introductory insight into its significance. My hope is that these principles prove as beneficial to you as they have been to me on my journey. Even if you don’t embrace all these principles, they provide an alternative perspective on how things could be approached and developed. Maybe it will raise some questions to you as well.

Thank you!





