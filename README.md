# csci-ga-2433-011-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CSCI-GA.2433-011 Homework 4 Solved](https://www.ankitcodinghub.com/product/csci-ga-2433-011-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93527&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI-GA.2433-011 Homework 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column">
Complete Procedure Review: For your convenience a summary is provided.

Input: A relational schema (informally, a relation) R and a set of FDs α.

Output: A set of relational schemas (informally, relations) such that the decomposition (a formal term for the set) satisfies the conditions

• It is lossless join

• It preserves dependencies

• The resulting tables are in 3NF.

Procedure:

1. Find a minimal cover for α, say ω

2. Produce a relation from each FD in ω by combining the attributes from both the LHS

and the RHS

3. One by one, remove a relation that is a subset of another relation 4. If (at least) one of the relations contains a key of R, you are done

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
5. Otherwise, add a relation that is a key for R

Example 1. Assume that I am supposed to do the above for R = ABC with FDs 1. AB→C

2. A→B

I attempt to remove B from LHS of (1). The new set of FDs is

1. A→C

2. A→B

The new set can only be stronger than the old set to test for equivalence, I attempt to prove (1) of the new set from all of the old set. Doing that I get:

A + = ABC

and as I get the RHS of the new (1), the new set is equivalent to the old set.

Nothing else can be attempted, so my last set (here the second) is a minimal cover.

I now create relations AB

AC

Nothing can be removed.

I now test whether at least one of the relations contains a key for R. Using my FDs, I compute

AB + = ABC.

I conclude that AB contains a key for R and I am finished.

Now 7 Problems for you to work on (10 points each with a total of 70 points):

<ol>
<li>(10 points) You are given the application described in slide 7/39. Do not assume any knowledge, such that the business rules are already in a nice format. You are just given the schema and the set of FDs that it satisfies. Follow the procedure in the above “Complete Procedure Review”. Do not skip any steps. This means that you have to compute every closure of the sets of attributes that you need and you need to show that your minimal cover is indeed a minimal cover, as otherwise you do not know that it is a minimal cover.</li>
<li>(10 points) You are given a relational schema satisfying some FDs, among them A → B. Explain why ABC cannot be a key of the schema.</li>
<li>(10 points) Using the heuristics described on slides 7/134–7/135 and providing full details and explanations, compute all the keys of R = ABCDEFGH given the FDs
• A→AB • A→G • C→A • D→G • F→GH • H→AF
</li>
<li>(10 points) You are given a relational schema R = ABC, satisfying the following FDs • A→B</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
• A→C

• B→C

(a) Which normal forms are satisfied? (Ignore 2NF) (b) A decomposition into AB and AC is proposed.

• Which normal forms are satisfied by AB and AC?

• Show by a small example that the dependencies are not preserved.

<ol start="5">
<li>(10 points) You are given a relational schema R = ABC, satisfying the following FDs
• A→B • A→C • B→C

(a) Which normal forms are satisfied? (Ignore 2NF) (b) A decomposition into AC and BC is proposed.

• Which normal forms are satisfied by AC and BC?

• Show by a small example that the decomposition is not a lossless-join

decomposition.
</li>
<li>(10 points) You are given a relational schema R = ABCDEFGH, satisfying α, the set of
FDs

• A→D

• A→E

• AG→H • BF→H • C→H • E→D

• F→B

(a) Compute ω, a minimal cover for α.

Follow the procedure in the above “Complete Procedure Review”. Do not skip any steps. This means that you have to compute every closure of the sets of attributes that you need and you need to show that your minimal cover is indeed a minimal cover, as otherwise you do not know that it is a minimal cover.
</li>
<li>(10 points) You are given a relational schema R = ABCDEFGH, satisfying α, the set of FDs
• AB→CD • A→E

• B→FG • E→AH

You are told that α is a minimal cover, and you may believe that. (a) Find a decomposition satisfying the conditions in the above “Complete Procedure Review”.
</li>
</ol>
</div>
</div>
</div>
