This repo is for recruiters interested in my experience and for anyone looking for a resume example or template. You can find my resume in English and Spanish under [My Resumes](#my-resumes).

# LaTeX Resume Template

Modern templates tend to be extremely rigid, making it impossible in most cases to make slight modifications to get a document exactly as you like.
That is why I built my own light template, whose simplicity makes it easy to use and tune.

Some basic LaTeX knowledge helps if you want to modify the template.

The file `resume.tex` contains the commands to build your resume.
My own versions are in `english.tex` and `spanish.tex`.

## Features

The main sections are Education, Research Papers, Selected Talks, Work Experience, Honors, Teaching Assistantships, and Projects.
Any of these can be skipped if not relevant or if you do not have that kind of experience.

- `\contactinformation` builds the header with your name, email, personal website, Google Scholar, and LinkedIn. Edit this command in `resume.tex` to use your own details.
- `\begin{concept}{Title} ... \end{concept}` groups entries under a section title.
- `\institution` lists a university, a degree or courses taught, and the dates.
- `\annotation` adds a lighter line below an entry, such as a research visit or relevant courses.
- `\job` pairs a paper title with its venue or status, or a job title with its location and dates.
- `\desc` adds the authors below a paper or describes the impact you had in a job. For work experience, I try to follow the pattern “Accomplished X as measured by Y, by doing Z.”
- `\talktopic` groups talks and posters on the same research topic.
- `\data` puts an entry on one line with its location or date on the right.
- `\enumeration` puts a label and its contents on one line, as in Research Interests or Languages.

## Setup

You can either clone this repository and work with it in any text editor of your choice, provided that you have a TeX compiler, or download it and use it in an online LaTeX editor such as [Overleaf](https://www.overleaf.com/).

# My Resumes

Here are the compiled versions of my resumes.
I am currently looking for a summer research internship in algorithmic game theory or combinatorial optimization, with a particular interest in learning in games and mechanism design.
I am open to relocate anywhere within the United States.

- [English Version](./temp/english.pdf)

- [Spanish Version](./temp/spanish.pdf)

For research or internship opportunities, feel free to email me at [cjp276@cornell.edu](mailto:cjp276@cornell.edu).

Check my [LinkedIn profile](https://www.linkedin.com/in/cristianpalmaf/) and my [personal website](https://cristianpalmafoster.github.io/).
