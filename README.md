# no-js-but-css
css techniques to mimic javascript functionality


Types of states:

## Toggled state (boolean)
With inputs
<input type="checkbox">

With the native dialog 'open' attribute
<dialog open>


## Any state 

//any state (as string)
<input value="state" type="radio">

//url target 
#state


## Form requests without navigating

Set request target to be a iframe
<form target="target-frame" action="/api/endpoint">
</form>
<iframe name="target-frame" hidden>

Use label to also change some state while performing a form submit
<--inside form -->
<button>
<label for='x'>Click</label>
</button>
<--inside form -->