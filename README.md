<h2>Overview</h2>
<p>This repository is created with a purpose of testing different data structures in python with the main goal of creating an AI program. By analyzing the user's behaviour and vocabulary it will be able to have a meaningful conversation with the user.</p>

<h2>How the AI program works exactly?</h2>
<p>
  <list><ol><li>After the program has been started, it asks the name of the User and how the User would the AI to be called.</li> 
    <li>After receiving the comma-separated answers, the program separates them into two elements of a list using the function split() and tries to reach and scan stored data from a foreign text file about the User. <ol><li><b>If this procedure is commitable</b>, the program commit this action and greet the User as an old friend.</li><li><b>Else</b> the User is asked to describe themselves with a simple sentence. Then User's reply is being analyzed with a function, which separates the words of the sentence into elements of a list, and browses for each word in the words Python dictionary using an iteration variable. If it do not find a word, the User will be asked to write a synonim. With an iteration variable, it is being searched in the words dictionary. If the program do not find the synonim, the User is asked to write an opposite word and the type of the originial word. Then, the information about the original word is being stored in a foreign text file, and in the words Python dictionary in the following order:original word,synonim,opposite,word type. For instance:tasty,delicious,flavourless,adjective. At the end of the analysing process, the User's characteristics, for instance happy and funny, is stored in a foreign text file, which is named User's_name.txt.</ol></li></li>
  <li>
    The AI starts a conversation with a basic line, for instance "How's it going?". If the AI has stored data about the User's hobby/hobbies, then it asks about one of the User's hobbies using a basic line, for instance:"How's it going with tennis?"
  </li>
  </ol></list></p>




<h2>Terms of use</h2>
<p>By using this code, you agree to the following terms:<list><ol>
<li>You may <b>not</b> claim this code as your own.</li>
<li>Redistribution or modification of the source code is permitted only if proper credit is given to the original author.</li>
</ol></list></p>
