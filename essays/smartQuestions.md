---
layout: essay
type: essay
title: "How to get a hackers attention"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: true
labels:
  - Smart Questions
  - Stupid Questions
  - StackOverflow
  - Answers
---

<div class="text-center p-4">
<img width="500px" class="rounded center pe-4" src="../img/essaySmartQuestions/questionMeme.jpeg">
</div>
<br>
Nowadays, technology is everything. But technology could not exist without software. Today, there is a vast amount of open-source resources available to help people learn programming. Although thousands of programming languages exist, there are always experienced programmers willing to share their knowledge. In addition to learning tools, there are forums and websites where experienced developers and hackers volunteer their time to help solve people's issues. But how do they choose which questions to answer when there are thousands of them? That’s where smart and stupid questions come into play.  

According to Eric Raymond, stupid questions are vague, show no effort, and are easily searchable. It is interesting to browse Stack Overflow not to find an answer, but to analyze the types of questions being asked. I realized that many questions are well-structured, in-depth, and demonstrate that the asker has put in effort to solve their own problem before seeking help. However, I was able to find an example of a stupid question on the platform:  

#### **Example of a Stupid Question**  
[How do I undo the most recent local commits in Git?](https://stackoverflow.com/questions/927358/how-do-i-undo-the-most-recent-local-commits-in-git/6866485#6866485)  

> *I accidentally committed the wrong files to Git but haven't pushed the commit to the server yet.*  
>  
> *How do I undo those commits from the local repository?*  

In this question, the asker shows no effort in solving the problem before asking. This is also a question that could be easily found on the internet with a quick search. Despite this, the asker still received a very detailed and undeserved answer, which clearly explained what to do and included the necessary commands to solve the problem.

On the other hand, smart questions are well-researched, clear, and demonstrate that the asker has put in effort before asking for help. One important aspect of asking a smart question is displaying the fact that you have attempted to solve the problem yourself and learned something from it. The best way to get a rapid and helpful response is to ask like an intelligent, confident, and thoughtful person who just needs help with one specific issue, as Raymond mentioned in his article "[How To Ask Questions The Smart Way](http://www.catb.org/esr/faqs/smart-questions.html)". Now, let’s delve into Stack Overflow and find an example of a smart question.  

#### **Example of a Smart Question**  
[How to use `glob` to find files recursively?](https://stackoverflow.com/questions/2186525/how-to-use-to-find-files-recursively)  

> *I would like to list all files recursively in a directory. I currently have a directory structure like this:*  
>  
> ```
> src/main.c  
> src/dir/file1.c  
> src/another-dir/file2.c  
> src/another-dir/nested/files/file3.c  
> ```  
>  
> *I've tried to do the following:*  
>  
> ```python  
> from glob import glob  
> glob(os.path.join('src', '*.c'))  
> ```  
>  
> *But this only retrieves files directly in the `src` subfolder, e.g., I get `main.c` but not `file1.c`, `file2.c`, etc.*  
>  
> ```python  
> from glob import glob  
> glob(os.path.join('src', '*.c'))  
> glob(os.path.join('src', '*', '*.c'))  
> glob(os.path.join('src', '*', '*', '*.c'))  
> glob(os.path.join('src', '*', '*', '*', '*.c'))  
> ```  
>  
> *But this is obviously limited and clunky. How can I do this properly?*  

In this question, the asker clearly explains their problem and provides detailed context about what they are trying to accomplish. They also show the effort they have put into solving the issue by listing the solutions they have attempted and why those solutions did not work. This is an excellent example of how to ask a well-structured question. The answers provided are clear, efficient, and easy to follow, showing that well-formed questions receive thoughtful responses.  

<img width="250px" class="rounded float-start pe-4" src="../img/essaySmartQuestions/stupidQuestionMeme.jpeg">

## **Conclusion**  
Software development can be tricky, and you may encounter issues that, despite extensive research and troubleshooting, you can't solve. Eric Raymond makes a compelling point that I hadn't considered before: *How can I structure my questions in a way that encourages experts to help me?*

After analyzing various questions on [Stack Overflow](https://stackoverflow.com), I realized how thorough and well-structured some questions are. These can serve as templates for when I need to ask a **smart question** myself.  

In short, **smart questions** are well-thought-out and encourage helpful responses, while **stupid questions** waste everyone's time.  
