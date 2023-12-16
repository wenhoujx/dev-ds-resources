# dev-ds-resources

This repo compiles resources can be helpful for DS and SDE job-seekers.

## Contact Me

- If you find this repo helpful, please give it a star
- connect with me on [linkedin](https://www.linkedin.com/in/wenshuai-hou-4a11834b/)
- add me on wechat: nilnilnullnull

## certification and training

- [databricks free training](https://www.databricks.com/resources/learn/training/lakehouse-fundamentals?scid=7018Y000001Fi0eQAC&utm_medium=paid+search&utm_source=google&utm_campaign=17882079543&utm_adgroup=140434566878&utm_content=training&utm_offer=lakehouse-fundamentals&utm_ad=665885915712&utm_term=databricks%20certification&gad_source=1&gclid=Cj0KCQiA4NWrBhD-ARIsAFCKwWtUNRpeQ8jTGQ_gfdKSzWPqMJfPp6cWhTqQSfnN4iYj60JTOo9pXs0aAoiYEALw_wcB)
- [aws certification](https://www.aws.training/certification)
- [snowflake training](https://www.snowflake.com/webinar/virtual-hands-on-labs/virtual-hands-on-lab-from-zero-to-snowflake-2023-12-20/?utm_source=google&utm_medium=paidsearch&utm_campaign=na-us-en-brand-core-phrase&utm_content=go-rsa-evg-vh-next-vhol-americas&utm_term=c-g-snowflake-p-657474892216&gad_source=1&gclid=Cj0KCQiA4NWrBhD-ARIsAFCKwWvh8C0-2EaGegxCMNW9pl__SBBQZkN353Fa_BCYLkRx2VQZN0zNP3UaAsKyEALw_wcB)

## FAQ

### Climb the ladder?

Mostly two ways:

1. Switch to more visible team within the company.
2. Switch to another company, get a higher title and salary, and keep doing it.
3. Combine the two above.

### Recruiter asked for salary expectation?

Don't tell, keep all your cards to yourself. If you tell, you will lose negotiation power. If they insist, tell them:

1. ask for the range of the role you are applying for, and tell them the higher end matches your expectation. Or tell them that range is too low in rare cases.
2. tell them you are open to negotiation, and you are looking for a good fit.
3. tell them you prioritize the role and the team and personal growth over the salary.

The best way of negotiation is to have multiple offers, and let them compete for you.

### Too many openings, how to choose which to apply?

If they don't limit the number of applications, apply all of them. It's a numbers game, the more you apply, the more likely you will get an interview.

Talk to the recruiter, ask them to help you choose. Find recruiters with "we're hiring" tag and talk to them.

List all of the opening, ignore the ones you don't understand, pick the ones you roughly know what it is, and apply.

### Python for interview lang?

Yes, python is definitely the best language for interview, it's concise, batteries included. Most interviewers know about Python. Python is also a good skill to have since it's widely used in production software.

### Can't fit in current team?

Two skills you must have to thrive:

1. Fit in the team. Chinese are going to be the minority in most companies, you will have to learn how to fit in.
2. Create connections with other teams in the company. Pay attention to networking with other teams in the company, and be open to opportunities.

### Should i get certificates? aws? udemy?

My personal experience is yes for east coast, no for west coast.

Pure tech firm even don't care about your degree, they care about your skills and experience.

East coast firms are more traditional, fintech or gov constractors pay some attention to certificates, especially aws, e.g. capitalone, bloomberg, booz allen hamilton, etc.

### Can't debug during coding interview?

Phycologically, you should view this as a pair programming collaboration session, you are not expected to solve the problem by yourself.

- communicate with the interviewer, ask questions, make sure they agree with your approach before coding.
- if you get stuck, walk and talk through your code with the interviewer, they should give you some hints if they see it.

Again, view this as an collaboration session, not a test. Experienced interviewers will make sure you have a good experience. They know you can solve the problem given a proper IDE and breakpoints. They want to know if you can actually write code, if you can handle stress, if you can communicate, if you can collaborate.

There are some tricks I use:

- Play dumb, if a problem has a slow but easy to write solution, propose it to the interviewer. Once they give you a green light, you should write the easy to write solution first. Later you should mention you can use some fancy algo or data structure for a better solution.
- If you are not sure about the syntax, ask the interviewer. They will tell you.
- Write the code in a way that you can easily debug, e.g. save the results in an array, return its length, instead of using a counter.
- Write your code in blocks, write some easy test for each block before moving on to the next one.
  - If you write and finish the whole code in one go, you will have a bug, and it's unlikely to be interactive with the interviewer.
- Know language batteries well and use them, for example in python, use `bisect` for binary chop, use `Counter` for counting, use `defaultdict` for grouping, use `heapq` for min-heap, use `string.rindex` to find first occurrence from right, You can always tell the interviewer you are testing if the basic idea works, and you will write your own implementation later.
  - it's a bonus that you know those tools well and can use them. Often the interviewer won't ask you to handroll them later if you showed enough coding proficiency already.

### AI LLM impact to SDE?

There are impact, but not as much for senior roles.

Senior SDE spend more time reading code, it's great LLM can help you write them. They spend time to design arch, understand tradeoffs, writing proposals, all of which LLM can help, but can't replace right now.

E.g. Senior UI developer creates amazingly consistent UX that's out of scope for LLM right now.

E.g. Senior BE dev designs message queue to database and sync to a secondary search engine. LLM can't design the whole system for you b/c they don't know the domain or the data modeling.

### Internal referral or online application?

Referral is usually better, [teamblind](https://www.teamblind.com/) has lots of people willing to refer you. They get the bonus if you get hired.
I found teamblind easier to get referral than cold reach out on linkedin.

Don't dismiss online application (or 海投), my personal experience is this is a numbers game, the more you apply, the more likely you will get an interview.

### Does intern or master degree count as working experience?

It depends on the company.

Some job description state it explicitly, e.g. "3 years of working experience or 1 year of working experience with a master degree".

My general rule is intern experience counts, and master degree counts as at least 2 year of working experience.

Don't be shy, apply that position and you will find out, there is nothing to lose other than time spent on that cover letter.

### What are project opportunities for students

It's hard to come up with a project on your own, you should find a team or a community.

- [kaggle](https://www.kaggle.com/), good for DS
- Meetup has local communities, go to bigger meetups, usually someone will pitch an idea, you can join the one you are interested in.
- School projects, lots of graduate program recruits graduate or undergraduate students to work on projects. Go talk to PHD students or professors, don't be shy.
- Open source, i don't think this has good ROI, rarely a graduate student can contribute to a project in a major way unless you are really into it. Reading their code is always learning and fun.
- github/Youtube resources, there are quality youtube walkthrough on how to build something.
  - [how to build x](https://github.com/codecrafters-io/build-your-own-x)
  - [projets to learn aws](https://www.youtube.com/watch?v=06VgLTqNvU8)

### What are high level job categories for SDE, their skill sets and their career path?

Categories:

- frontend FE: UI, mobile UI, workflow study, user experience(UX). FE sits closer to client and user than BE, so it requires more use case analysis.
- backend BE: data modeling, application layer, database, search engine, cache, message queue. In general, BE has more scopes than FE, but maybe less visibility, unless the stack is on fire.
- devops: setup infra to support dev and production, CI/CD, monitoring, alerting, logging, security.
- SRE: people who fights fires, bad WLB during on-call, but good pay and more vacations.

Language and skills:

- FE: javascript, typescripts, npm, node, vite, react, css, html.
- BE: java, C++, python are the major ones, though there are more langauge options than FE depending on the company, e.g. golang, scala, rust, etc.
- devops: python, bash, terraform, ansible, kubernetes, docker, aws, gcp, azure, etc.
- SRE: roughly same as devops.

career path: (the following content is highly opinionated and biased)

- FE: they are usually more social, i've seen many become product managers.
- BE: they are usually more technical, architects or managers are usual path.
- devops: same as BE
- SRE: managers, i rarely see an SRE become an architect.

### Should i put years of experience next to my language skills?

It's not necessary. You can use bold or highlight on skills you want to call out, or you can split to master proficincy or normal proficincy.

It's hard to count the YOE for a language, since you may first learned python in high school, use it on and off for 5 years, and used it intensely during your master research. Count the 5 years "gap" or not is personal choice.
