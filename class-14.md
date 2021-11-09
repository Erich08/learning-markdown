# Transform

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

> The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

```
div {
  -webkit-transform: scale(1.5);
  -moz-transform: scale(1.5);
  -o-transform: scale(1.5);
  transform: scale(1.5);
}
```

## Transitions & Animations

> One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.

```
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```

> It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. The display property, for example, may not be transitioned as it does not have any midpoint. A handful of the more popular transitional properties include the following.

- background-color
- border-width
- clip
- font-size
- left
- margin
- min-height
- outline-color
- padding
- text-shadow
- visibility
- z-index

## Transition Duration

> The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.

When transitioning multiple properties you can set multiple durations, one for each property. As with the transition-property property value, multiple durations can be declared using comma separated values. The order of these values when identifying individual properties and durations does matter. For example, the first property identified within the transition-property property will match up with the first time identified within the transition-duration property, and so forth.

If multiple properties are being transitioned with only one duration value declared, that one value will be the duration of all the transitioned properties.

## Transition timing

> The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.

The linear keyword value identifies a transition moving in a constant speed from one state to another. The ease-in value identifies a transition that starts slowly and speeds up throughout the transition, while the ease-out value identifies a transition that starts quickly and slows down throughout the transition. The ease-in-out value identifies a transition that starts slowly, speeds up in the middle, then slows down again before ending.

Each timing function has a cubic-bezier curve behind it, which can be specifically set using the cubic-bezier(x1, y1, x2, y2) value. Additional values include step-start, step-stop, and a uniquely identified steps(number_of_steps, direction) value.

When transitioning multiple properties, you can identify multiple timing functions. These timing function values, as with other transition property values, may be declared as comma separated values.

## Project Aristotle

Project Aristotle was started in 2012 by Google. The idea was to figure out what made their employees more effective/productive. One of the researchers assigned to this project was a recent Yale graduate named Julia Rozovsky.

The project started out by reviewing academic studies on that focused on how teams worked. They wanted to know what made teams more effective than other teams. They explored ideas such as did all the team members have similar interests? Were the team members motivated by similar rewards?

Even with all the data they had collected on teams at Google, it was nearly impossible to find any discernable patterns. Or that the composition of any team had any effect. They looked at a total of 180 teams across the company.

As the research continued, they came across was researchers refer to as "group norms." This norms are subjective and based on the group as a whole. That way I interpreted it it seems to be some sort of value system that the entire team can agree on. Some teams avoided any confrontation or disagreements while others embraced them. It went on to talk about how people who preferred to work alone set aside those "proclivities" to work with the group.

The article goes on to cite another study that was done in 2008 that was studying the collective IQ of groups. What they found was that teams who had an equal amount of conversation among its members throughout the day were far more successful than teams that had the majority of conversation take place amongs a select few members. Another interesting aspect was that some groups had individuals who were very smart, and other groups consisted of members who would be considered "average" intelligence but they performed similarly. The reason for this that was given is the latter team was able to leverage the collective strength of all its members to accomplish the tasks at hands. "Two heads are better than one" comes to mind. Another aspect of success was that all of the good teams had a high level of social sensitivity.

> We had lots of data, but there was nothing showing that a mix of specific personality types or skills or backgrounds made any difference. The ‘‘who’’ part of the equation didn’t seem to matter.
