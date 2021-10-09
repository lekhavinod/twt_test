---
title: Harry Potter
layout: demo_template
<!---comment: hello--->
author: J K Rowling
person: Harry Potter
country: United Kingdom
title: wizard
---
{%include lorem.txt%}

---

# Who am I?

I am {{page.person}}. I live with my aunt, uncle, and cousin brother at Little Whingings, Surrey, in {{page.country}}. My character was created by teh renowed auther {{page.author}}.

## My occupation ##
I am a {{page.title}} living in the ordinary world of non-magical people known as muggles. I graduated from the renowned wizarding academy in Scotland named *Hogwarts School of Witchcraft and Wizardry*.

### Something more about me ###
1. Strength
  - Courageous and compassionate
  - Endure hardships
  - Instinctive
  - Loyal

2. Weakness
  - Judgemental (and occasionally illogical)
  - Self absorbed
  - Emotional
  - Self sacrificing

### My family and friends ###

My immediate family are the Dursleys, but let's not go there. They hardly qualify to be called family. I was orphaned when my parents were murdered by dark {{page.title}} when I was a baby. And, I am the only surviving witness to that henious act.

Name | Gender | Profession| Relation|
---|---|---|---|
{{page.author}}|Female|Writer| A muggle who created my character (why did she have to be a muggle!)|
James Potter|Male|{{page.title}}|Father|
Lily Potter|Female|Witch|Mother|
Ron Weasly| Male|{{page.title}}| Friend|
Hermione Granger| Female | Witchcraft| Friend|
Sirius Black | Male | {{page.title}} | Godfather|
Severus Snape | Male | {{page.title}}| Professor and my secret savior|
Albus Dumbledore |Male| {{page.title}}| Founder of Hogwarts|
Remus Lupin|Male| {{page.title}}| Dark {{page.title}} expert|
Rubeus Hagrid| Male| Half-giant| Keeper of Keys and Grounds at Hogwarts|
Tom Marvolo Riddle| Male| {{page.title}}| Power-obsessed dark {{page.title}} a.k.a `You-Know-Who`, `He-Who-Must-Not-Be-Named`, and `Lord Voldemort`|

_There's more to me than just this page. Did you read the Harry Potter book series? If not yet, you just proved that you are a muggle of the top order!_

---
([^1] : It's not too late! I urge you to read the book series or watch the movies made on the book series. Personally, I recommend reading the books, it lets you weave your personal imagination of the world of wizardry and magic. I hope you find the experience enjoyable!)


{% for item in site.data.employee %}

{{item.ID}} : {{item.Name}}

{% end for %}
