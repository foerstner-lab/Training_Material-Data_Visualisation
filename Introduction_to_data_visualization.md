# Introduction to data visualisation

## Perception - the five senses

The five senses are the primary means by which humans perceive and
experience their environment. They include sight, hearing, smell,
taste, and touch. Sight is the ability to see objects and colors
through light waves that enter our eyes and stimulate specialized
cells called rods and cones in the retina. Hearing involves the
perception of sound by detecting vibrations in the air using hair-like
structures called cilia in the inner ear. Smell is the ability to
perceive odors through a network of olfactory receptors that detect
chemical compounds present in scents. Taste is the sensation of flavor
and texture, which involves the interaction between taste buds on our
tongue and various molecules present in food or drink. Touch is the
perception of pressure, temperature, and other tactile stimuli through
a network of nerve endings that detect these signals from our skin and
muscles. Together, these five senses enable humans to interact with
their environment, learn about it, and adapt to different situations
and experiences.

- sight (stimulus: light)
- smell (stimulus: chemical substance)
- touch (stimulus: presure / temperatur)
- taste (stimulus: chemical substance)
- hearing (stimulus: sound = presure)


## Encoding / decoding of data during visualisation

**Data encoding** refers to the process of representing numerical or
categorical information in a way that can be easily understood by
humans through visual means such as graphs, charts, or maps. During
data visualization, this encoded information is translated into
different types of visual representations like line plots, bar charts,
scatter plots, and pie charts, among others.

**Data decoding** refers to the process of interpreting these visual
representations to extract meaningful insights from the data. This
involves understanding how the various elements within a graph or
chart are related and what patterns they may reveal about the
underlying data. It helps forming a mental model of the visualised
data.

<figure id="fig:Encoding" width="800">
<img src="./images/Data_encode_visualisation_decode.png" />
<figcaption>Encoding and decoding during visualisation to form a mental model</figcaption>
</figure>


### Features / Attributes

Features can be
- **categorical** / **qualitative**
  - **Nominal**: Nominal features are categorical variables that have
    two or more categories without any inherent order or ranking among
    them. (e.g. eye color, type of bike)
  - **Ordinal**: These are features that represent a natural order. The
    values can be ordered but not necessarily equally
    spaced. (e.g. very bad, bad, good, very good)
- **numerical** / **quantitative**
  - **Discrete**: Discrete features are a type of variable in
    statistics and data analysis that represent countable, distinct
    values. (e.g. number of people, number of page visits per month)
  - **Continuous**: These are features that represent numerical data with
    infinite possibilities and can take any value within a range
    (e.g. height of person, weight of ships, distance between two
    locations)

## Aesthetics

Aesthetics - anciet greek αἴσθησις;

In the context of data visualization, aesthetics refer to the visual
properties and attributes used to represent data. Aesthetics play a
crucial role in making visualizations engaging, understandable, and
informative.

<figure id="fig:accuarcy" width="800">
<img src="./images/Aesthetics_and_accuracy.png" />
<figcaption>based on Mackinlay, 1986, <em>ACM Transactions on
Graphics</em>, <a
href="https://doi.org/10.1145/22949.22950">https://doi.org/10.1145/22949.22950</a></figcaption>
</figure>

## Misc

<figure id="fig:accuarcy" width="800">
<img src="./images/Color_vs_Shape.svg" />
<figcaption>Shape vs Color</figcaption>
</figure>



### Visualization Lecture: The Role of Interaction in Data Visualization

#### Why Interaction is Important in Visualization

Interaction in data visualization refers to the ability of users to manipulate and engage with the visual representation of data. This dynamic element enhances the user experience and makes the data exploration process more intuitive and insightful. Here are key reasons why interaction is vital:

1. **Enhanced Understanding**: Interaction allows users to engage with data in a more meaningful way, leading to deeper insights and better comprehension.
2. **Exploratory Analysis**: Users can explore different facets of the data, identify patterns, and uncover hidden relationships that static visualizations might not reveal.
3. **Personalized Experience**: Interactive visualizations can be tailored to meet the specific needs and preferences of different users, making the analysis more relevant and impactful.
4. **Increased Engagement**: Interactive elements keep users engaged and make the process of data exploration more engaging and enjoyable.
5. **Real-Time Feedback**: Users receive immediate feedback on their actions, allowing them to iteratively refine their queries and understand the data better.

#### Considerations for Interactive Visualization

When incorporating interaction into visualizations, several factors need to be considered to ensure effectiveness and usability:

1. **User Needs and Goals**: Understand who the users are and what they aim to achieve with the visualization. The interaction design should align with their tasks and objectives.
2. **Simplicity and Usability**: Ensure that the interactions are intuitive and easy to use. Overly complex interactions can overwhelm users and detract from the visualization's effectiveness.
3. **Performance and Responsiveness**: Interactive visualizations should be responsive and perform well, even with large datasets. Slow or laggy interactions can frustrate users.
4. **Accessibility**: Make sure the interactive elements are accessible to all users, including those with disabilities. This includes providing keyboard navigation and screen reader support.
5. **Context and Guidance**: Provide context and guidance for users to understand how to use the interactive elements. Tooltips, tutorials, and clear instructions can help users navigate the visualization effectively.
6. **Data Integrity and Security**: Ensure that the data remains accurate and secure throughout the interaction process. Users should trust the data they are interacting with.

#### Advantages of Interactive Visualization

1. **Deeper Insights**: Interactive visualizations facilitate a more thorough exploration of data, leading to richer insights.
2. **User Engagement**: Interactive elements make the data exploration process more engaging, encouraging users to spend more time analyzing the data.
3. **Flexibility**: Users can customize the visualization to meet their specific needs, making the analysis more relevant.
4. **Immediate Feedback**: Real-time interaction allows users to quickly test hypotheses and receive immediate results, speeding up the analytical process.
5. **Enhanced Communication**: Interactive visualizations can be more effective in communicating complex data stories, as users can explore the data at their own pace and focus on areas of interest.

#### Disadvantages of Interactive Visualization

1. **Complexity**: Designing and implementing interactive visualizations can be complex and time-consuming. It requires careful planning and technical expertise.
2. **Performance Issues**: Interactivity can introduce performance challenges, especially with large datasets or complex interactions. Ensuring smooth and responsive interactions can be difficult.
3. **Learning Curve**: Users may need to learn how to use the interactive elements effectively. Poorly designed interactions can lead to confusion and frustration.
4. **Accessibility Barriers**: Not all users may be able to fully engage with interactive elements, particularly those with disabilities. Ensuring accessibility can be challenging.
5. **Overwhelming Users**: Too many interactive options can overwhelm users and make the visualization less effective. Striking the right balance between interactivity and simplicity is crucial.

### Conclusion

Interaction in data visualization significantly enhances the analytical capabilities and user experience by allowing users to explore, manipulate, and personalize their data views. However, it is essential to carefully design and implement interactive elements, keeping in mind the users' needs, usability, performance, and accessibility. Balancing these factors can lead to highly effective and engaging visualizations that provide deep insights and a rewarding user experience.
