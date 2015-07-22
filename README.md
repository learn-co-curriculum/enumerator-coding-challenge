# Enumerator Coding Challenge

## Objectives of lesson

Become familiar using common iterators introduced in the previous lesson.


<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge I: Using `.each`</h1></div><div class='question-block'><p class='question-title'><p>Let&#39;s try out the enumerator methods we just learned. Refer back to the previous lesson to help you pass this challenge. </p>

<p>Below, we have a variable, <code>lunch_menu</code>, set equal to an array of lunch menu items.</p>

<p>Since you&#39;re super hungry and super excited about lunch, use the <code>.each</code> method to enumerate over the array and append a &quot;!&quot; to each menu item. You can use the <code>&lt;&lt;</code> on each menu item string to add an &quot;!&quot;. Like this: &quot;pizza&quot; &lt;&lt; &quot;!&quot;</p>
</p><div class='repl-answer-block'><textarea data-initial='lunch_menu = ["pizza", "sandwhich", "sushi", "soup", "salad"]

#code your solution using .each here' data-solution='["lunch_menu.each do |lunch_item|","\tlunch_item << \"!\"","end"]' data-validation='["assert_equal(response, [\"pizza!\", \"sandwhich!\", \"sushi!\", \"soup!\", \"salad!\"])"]' data-language='ruby' id='repl-0' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge II: Using `.collect`</h1></div><div class='question-block'><p class='question-title'><p>Below we have a variable, <code>nums</code>, set equal to an array of numbers. Enumerate over the array with the <code>.collect</code> method and return a new array of the same numbers, squared.</p>
</p><div class='repl-answer-block'><textarea data-initial='nums = [1, 2, 3, 4]

#code you solution using .collect here' data-solution='[" ","nums.collect do |num|","\tnum * num","end"]' data-validation='["assert_equal(response, [1, 4, 9, 16])"]' data-language='ruby' id='repl-1' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge III: Using `.select`</h1></div><div class='question-block'><p class='question-title'><p>Below we have a variable, <code>odds_and_evens</code>, set equal to an array of numbers. Use the <code>.select</code> enumerator to iterate over the array and return any even numbers. This about how to check if a number is even. Maybe google &quot;how to check if a number is even ruby&quot; or something like that...</p>
</p><div class='repl-answer-block'><textarea data-initial='odds_and_evens = [1, 3, 2, 18, 5, 10, 24]

#code your solution using .select here' data-solution='["odds_and_evens.select do |num|","\tnum.even?","end"]' data-validation='["assert_equal(response, [2, 18, 10, 24])"]' data-language='ruby' id='repl-2' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge IV: Using `.find`</h1></div><div class='question-block'><p class='question-title'><p>Below we once again have a variable, <code>odds_and_evens</code>, set equal to an array of numbers. This time, use the <code>.find</code> method to iterate over the array and return only the <em>first</em> array element that is <em>odd</em>.</p>
</p><div class='repl-answer-block'><textarea data-initial='odds_and_evens = [1, 3, 2, 18, 5, 10, 24]

#code your solution using .find here' data-solution='["odds_and_evens.find do |num|","\tnum.odd?","end"]' data-validation='[" ","assert_equal(response, 1)"]' data-language='ruby' id='repl-3' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge V: Using `delete_if`</h1></div><div class='question-block'><p class='question-title'><p>Below we have a variable, <code>cats_and_dogs</code>, set equal to an array of strings that are either cats or dogs. We all know that cats and dogs don&#39;t get along. Iterate over the array and delete from it any items that are dogs.</p>
</p><div class='repl-answer-block'><textarea data-initial='cats_and_dogs = ["cat", "cat", "dog", "cat", "dog", "dog"]

#code your solution using .delete_if' data-solution='["cats_and_dogs.delete_if do |pet|","\tpet == \"dog\"","end"]' data-validation='["assert_equal(response, [\"cat\", \"cat\", \"cat\"])"]' data-language='ruby' id='repl-4' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge VI: Using `include?`</h1></div><div class='question-block'><p class='question-title'><p>Below we have a variable, <code>famous_cats</code>, set equal to an array of famous cats. Use the <code>.include?</code> method to check and see if the array includes the string &quot;Maru&quot;.</p>
</p><div class='repl-answer-block'><textarea data-initial='famous_cats = ["Maru", "Lil Bub", "Grumpy Cat"]

#code your solution using .indlude? here' data-solution='["famous_cats.include?(\"Maru\")"]' data-validation='["assert_equal(response, true)"]' data-language='ruby' id='repl-5' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

<div>
</div><div class='quiz-block'><div class='quiz-title'><h1>Code Challenge VII: Using `any?`</h1></div><div class='question-block'><p class='question-title'><p>Below we have a variable, <code>quiet_and_loud</code>, that is set equal to an array of strings. Use the <code>.any?</code> method to iteratore over the array to determine if any of the words contained there are loud, or upcased.</p>
</p><div class='repl-answer-block'><textarea data-initial='quiet_and_loud = ["hi", "HI", "shhh", "WHAT?!"]

#code your solution using .any? here' data-solution='[" ","quiet_and_loud.any? do |word|","\tword == word.upcase","end"]' data-validation='["assert_equal(response, true)"]' data-language='ruby' id='repl-6' class='repl'></textarea></div><input type='submit' value='SUBMIT' class='assessment-btn btn btn-sm'><input type='button' value='SEE SOLUTION' class='assessment-btn solution-btn btn btn-sm btn-info'><div class='solution-repl-holder'><textarea class='repl-solution'></textarea></div></div></div><div>
</div>

