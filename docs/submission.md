---
layout: tabbed-assignment
---

# Submission Instructions

After completing the lesson:

1. Make sure that you have:
   - Commited changes to the **{{site.data.assignment.git-curr-branch}}** branch.
   - Pushed your changes to GitHub.
   - Confirmed that you see your changes on GitHub.
1. Then, **[make a copy][template.copy]** of the [submission template][template.link].
1. Rename the file and move it to your class folder on your Google Drive.
1. Complete the template.
1. Submit as usual.

{% include submission-boilerplate.html %}

<!-- Don't edit links here, change them in _data/assignment.yml instead, -->

{% if site.data.assignment.lesson   %}[lesson]: <{{site.data.assignment.lesson}}>     {% endif %}
{% if site.data.assignment.slides   %}[slides]:   <{{site.data.assignment.slides}}>   {% endif %}
{% if site.data.assignment.template %}[template.copy]: <{{site.data.assignment.template}}/copy> {% endif %}
{% if site.data.assignment.template %}[template.link]: <{{site.data.assignment.template}}> {% endif %}
