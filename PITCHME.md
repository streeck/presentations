---?image=images/servers.jpg&opacity=40
@title[Intro]

## @color[#ffffff](An overview of Microservices and a Flasky approach)

---
@title[Bio]
## But first...

#### A little bit about me @fa[smile]

+++?image=images/logo_1_large.png&size=auto

+++?image=images/flask-logo.png&size=auto 80%

+++?image=images/django-logo-positive.png&size=auto

+++?image=images/data_scientist.png&size=auto 80%

---
@title[Outline]
## Talk Outline

1. Microservices intro and why it's still relevant
2. The misconceptions, the benefits and the pitfalls
3. Flask as a contender
4. Overview

---?image=images/microservices-logo.png&size=auto
@title[Microservices and its relevance]

+++?image=images/google_trends.png&size=auto 80%

+++?image=images/gartner_hype_cycle.jpg&size=auto 80%

+++?image=images/tw_tech_radar.png&size=auto 90%

---?image=images/microservices-logo.png&size=auto
@title[Microservices intro and definition]

Note:
Has been around since 2014, not new.
Main points:
- Componentization via services
- Organized around business capabilities
- Decentralized governance and data management

+++?image=images/monolith_microservices.png&size=auto 92%

Note:
Examples:
- Unix command line

+++?image=images/microservices_definiton_1.png&size=auto 80%

---?image=images/audio_studio.png
@title[Components]

Note:
- Independently replaceable and upgradeable

+++?image=images/silos.png&size=auto 80%
@title[Organization around business capabilities]

Note:
Big organizations usually organize themselves around technology.

+++?image=images/cross_functional.png&size=auto 80%

Note:
- 2 pizza team from Amazon, american pizza of course
- Not only small, but direct contact with end-user, verticality towards the end-user

+++?image=images/conway_law.png&size=auto 80%

---?image=images/decentralization.png&size=auto 70%
@title[Decentralization]

+++?image=images/single_database.png&size=auto 80%

Note:
- Learned from C that shared global variables are bad...
- One big relational database used across the company, everyone stuck with one DB technology, a humongous Oracle DB for instance.

+++?image=images/multiple_databases.png&size=auto 80%

Note:
- Every service responsible for its own data
- No more integration through database
- Frees up services to use the data store that makes most sense

+++?image=images/diverse_stack.png&size=auto 92%

Note:
Just please, don't use Javascript ;)

---
+++?image=images/devops.png?&size=auto 80%

---

---?image=images/flask-logo.png&size=auto 50%

+++
@transition[none]
#### From flask's website

> Flask is a microframework for Python based on Werkzeug, Jinja 2 and good intentions.

+++
@transition[none]
#### From flask's website

> Flask is a microframework for Python based on Werkzeug, Jinja 2 and @color[#174792](__**good intentions**__).

+++?code=code_snippets/flask_intro.py&lang=python&title=Hello... World?

@[1-2](Import and Flask class instantiation)
@[5-7](Simple endpoint)

---?image=images/cthulhu.jpg&size=auto 92%

+++?image=images/simple_dictionary.png&size=auto 80%

+++?image=images/minimalist_dictionary.png&size=auto 80%

+++?image=images/minimalist_use_over_time.png&size=auto

---?image=images/test.gif&size=auto 50%

---

# Questions?
