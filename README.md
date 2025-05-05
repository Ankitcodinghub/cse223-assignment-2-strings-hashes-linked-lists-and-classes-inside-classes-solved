# cse223-assignment-2-strings-hashes-linked-lists-and-classes-inside-classes-solved
**TO GET THIS SOLUTION VISIT:** [CSE223 Assignment 2-Strings, Hashes, Linked Lists and Classes Inside Classes Solved](https://www.ankitcodinghub.com/product/cse223-assignment-2-strings-hashes-linked-lists-and-classes-inside-classes-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95917&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE223  Assignment 2-Strings, Hashes, Linked Lists and Classes Inside Classes Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
This assignment is signi􏰄cantly more complex that Programming Assignment 1, yet the actual amount of code you need to write may be surprisingly small. Again: work methodically and ask questions along the way.

The biggest challenge here is thinking of objects as self-contained entities that include data and functions for interacting with that data. Once you come to terms with this, the code starts to almost write itself!

This also won’t happen in a day: it will take multiple coding sessions for your brain to settle into this way of thinking. Start early! Starting the project a day or two before it’s due won’t su􏰅ce, and you’ll su􏰃er throughout the reminder of the class if you do so.

Do not use Eclipse, IntelliJ, or any other IDEs: work from the command line on the Linux server (or your own Linux environment). This will ensure you know the syntax for de􏰄ning classes, writing a main method, and so on.

1 Description

For assignment 2, you are going to implement a new Java class named Indexer, which will allow you to read the contents of a text 􏰄le and create an index showing the position(s) of each word in the 􏰄le.

2 Details

Your class must be named Indexer. You are only responsible for writing this class, but you’ll want to develop a main program (or several programs) to help you test it.

</div>
</div>
<div class="layoutArea">
<div class="column">
Constructor

The class should have a single constructor:

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Indexer ind=new Indexer(); which does nothing in particular!

Public Methods

You must provide the following public methods:

<pre>  public boolean processFile(String filename);
</pre>
Usually the 􏰄rst method you would call after constructing an Indexer. Opens the given 􏰄lename, reads its contents and, while reading, builds an index. Returns true if the process succeeds, false if it fails (typically because the 􏰄le cannot be read). Note that this method never prints anything (including error messages).

Once you’ve built an index, you can use the following methods to examine it: public int numberOfInstances(String word);

If processFile() has not yet been successfully run, return -1. Otherwise, return the number of times that the given word appears in the processed 􏰄le. If the word does not appear, return 0.

<pre>  public int locationOf(String word, int instanceNum);
</pre>
If n is the value of instanceNum, then this method returns the location of the nth occurrence of word (NOTE the 􏰄rst occurrence is 0; the second is 1; and so on). If processFile() has not yet been successfully run, return -1. If word does not appear in the processed 􏰄le, return -1. If instanceNum is too small (&lt;0) or too large (≥the number of occurrences of word), return -1.

<pre> public int numberOfWords();
</pre>
Return the total number of unique words in the index (-1 if processFile() has not yet been suc- cessfully run).

<pre>  public String toString();
</pre>
Return the toString value of your hash table. If processFile() has not yet been successfully run, return null

Private Methods

You should also implement the following private methods:

<pre>  private String cleanupWord(String word);
</pre>
Remove all characters from word that are not letters, according to Character.isLetter(). Return an upper-case version of the resulting string (which could be empty, if none of its original characters were letters).

<pre>  private void addReference(String word, int location);
</pre>
Add location to the end of word’s linked list. If word is not presently in the hash, add it 􏰄rst (with an empty linked list). If no 􏰄le has been processed, do nothing (don’t throw an exception!)

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Fields

You need one private 􏰄eld in your class, named index. This should be an object of type HashMap.

3 Implementation To process a 􏰄le:

<ul>
<li>open it using Scanner (if an error occurs, immediately return false);</li>
<li>construct a HashMap named index. Keys should be Strings, and values should be LinkedLists
of Integers;
</li>
<li>initialize a position counter to 0</li>
<li>read words using hasNext() and next();</li>
<li>clean the word using cleanupWord();</li>
<li>if the word is not empty, increment the position counter and then call your addReference() method (pass it the word and the position counter). addReference() functions as follows:
􏰆 if the word is not in the index, add it along with an empty linked list 􏰆 add the position counter to the end of the linked list
</li>
<li>On end of 􏰄le, close the Scanner and return true.
cleanupWord() can be a single for loop that builds a return string based in a character-by-character examination of the incoming string. Look at String.charAt() and Character.isLetter().

The remaining methods are mostly just wrappers to calls to other methods.

4 Testing

Here are a sample main program, test 􏰄le and expected output that can be used to test your Indexer (but make sure you do much more testing than this!)

Sample Code

(This sample program is available on the linux server at /tmp/PA2Test.java; the test􏰄le is at /tmp/test􏰄le.txt Copy these to your own directory to use them.)

<pre>//
// Test code for Indexer class
// njm
//
</pre>
<pre>public class Main
{
</pre>
<pre>  public static void main(String[] args)
</pre>
3
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<pre>  {
    Indexer ind=new Indexer();
</pre>
<pre>// make sure things don't blow up
    System.out.println("Before processing, ind="+ind);
    System.out.println("Before processing, numberOfInstances returns "+
</pre>
<pre>                        ind.numberOfInstances("TEST"));
    System.out.println("Before processing, locationOf returns "+
</pre>
<pre>                        ind.locationOf("TEST",1));
    System.out.println("Before processing, numberOfWords returns "+
</pre>
<pre>                        ind.numberOfWords());
</pre>
<pre>// process a non-existent file
    boolean status=ind.processFile("badfile.bad");
</pre>
<pre>    System.out.println("\nAfter processing bad file, status="+status);
    System.out.println("\nAfter processing bad file, ind="+ind);
    System.out.println("After processing bad file, numberOfInstances returns "+
</pre>
<pre>                        ind.numberOfInstances("TEST"));
    System.out.println("After processing bad file, locationOf returns "+
</pre>
<pre>                        ind.locationOf("TEST",1));
    System.out.println("After processing bad file, numberOfWords returns "+
</pre>
<pre>                        ind.numberOfWords());
</pre>
<pre>// no process a good testfile
    status=ind.processFile("testfile.txt");
</pre>
<pre>    System.out.println("\nAfter processing good file, status="+status);
    System.out.println("\nAfter processing good file, ind="+ind);
    System.out.println("# of instances of BADBADBAD="+
</pre>
<pre>                        ind.numberOfInstances("BADBADBAD"));
    System.out.println("# of instance of TEST="+
</pre>
<pre>                        ind.numberOfInstances("TEST")+"\n");
// iterate over all instances (plus a few out of range)
</pre>
<pre>    for (int i=-1;i&lt;=ind.numberOfInstances("TEST");i++){
      System.out.println("Instance " + i + " is at location "+
</pre>
<pre>                          ind.locationOf("TEST",i));
</pre>
}

<pre>    System.out.println("\n# of unique words="+ind.numberOfWords());
  }
</pre>
}

test􏰄le.txt

<pre>This, is a test! So it is!!!, so it is,
and so, I say, yes? or no! Time to test this.
</pre>
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<pre>What will we do? :)  Test test test
Yes! Goodbye!
</pre>
Corresponding Output (note that 􏰁THIS􏰂 occurs at position 1, not 0)

<pre>Before processing, ind=null
Before processing, numberOfInstances returns -1
Before processing, locationOf returns -1
Before processing, numberOfWords returns -1
</pre>
<pre>After processing bad file, status=false
</pre>
<pre>After processing bad file, ind=null
After processing bad file, numberOfInstances returns -1
After processing bad file, locationOf returns -1
After processing bad file, numberOfWords returns -1
</pre>
<pre>After processing good file, status=true
</pre>
<pre>After processing good file, ind={A=[3], NO=[17], OR=[16],
YES=[15, 29], I=[13], IS=[2, 7, 10], SAY=[14], TIME=[18],
IT=[6, 9], DO=[25], WHAT=[22], WE=[24], GOODBYE=[30],
TEST=[4, 20, 26, 27, 28], AND=[11], THIS=[1, 21], WILL=[23],
TO=[19], SO=[5, 8, 12]}
</pre>
<pre># of instances of BADBADBAD=0
# of instance of TEST=5
</pre>
<pre>Instance -1 is at location -1
Instance 0 is at location 4
Instance 1 is at location 20
Instance 2 is at location 26
Instance 3 is at location 27
Instance 4 is at location 28
Instance 5 is at location -1
</pre>
<pre># of unique words=19
</pre>
5 Grading

Your assignment must be downloadable from GITLab by me in order to be graded. I will download using the command:

<pre>git clone git@gitlab.com:yourGITid/CSE223PA2.git
</pre>
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
You can mimic this yourself to con􏰄rm that your repository is located and named correctly. There’s no sure way to check that you have added me as a reporter: just make sure you do!

Points are awarded as follows:

<ul>
<li>Project can be downloaded and compiled: 20 points</li>
<li>Indexer class de􏰄ned: 5 points</li>
<li>processFile ingests the given 􏰄le and stores some cleaned words in a HashMap: 10 points</li>
<li>processFile associates a LinkedList containing at least one location with (some) words: 5 points</li>
<li>processFile saves all words and a LinkedList with some locations: 5 points</li>
<li>processFile saves all words and a LinkedList with all locations: 5 points</li>
<li>toString, numberOfWords, numberOfInstances and locationOf: 20 points (5 points each if perfect)</li>
<li>correct handling of uninitialized index(processFile not successfully run): 5 points</li>
<li>required private methods implemented: 10 points</li>
<li>style: 15 points if you have all of the following:
􏰆 consistent indenting, placement of braces, etc.

􏰆 all code commented (every line unless it’s extremely obvious why that line is there) 􏰆 each method described by an introductory block of comments.

􏰆 entire class described by a block of comments in the beginning (in your own words).
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
