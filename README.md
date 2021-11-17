# Core Domain Charts

Core Domain Charts help you to visualise the strategic importance of each (sub)domain or business capability in your architecture allowing you to make business model-aligned architectural decisions.

[Core Domains](https://www.youtube.com/watch?v=PBRluTD5oHo) are the parts of your domain where the expected [ROI](https://www.investopedia.com/terms/r/returnoninvestment.asp) is greatest, and deserve the highest focus.

The true power of this technique is the conversations that it triggers, especially cross-discipline. Complexity is something that engineers can gauge whereas business differentiation is provided by product managers or business stakeholders.

![alt text](resources/core-domain-chart-template.jpg "Core Domain Chart")

## How to Use

There are a variety of ways the Core Domain Chart can be used, but it's important not to try to and visualise all the possible information in a single diagram. Below are multiple versions showing different types of information to choose from.

### (Sub)Domain/Bounded Context Portfolio 

This is the simplest flavour. Simply plot each of your (sub)domains or bounded contexts on the chart to get a relative sense of ordering between them.

### Context Map With Team Topologies

You can augment your Core Domain Charts with the dependencies between your bounded contexts and the type of [Team Topologies](https://github.com/TeamTopologies) Interaction Mode in play.

### Architecture Migration

With a slight tweak of the y-axis label, core domain charts can be used to plan the order in which you migrate from your current architecture to your target architecture.

![alt text](resources/architecture-migration-core-domain-chart.jpg "Architecture Migration Core Domain Chart")

## Suggestions for Measuring Complexity and Differentiation

Firstly, measuring complexity and differentiation of your domains is hard and is usually quite subjective. Strategy is a bet on the future, so you can never be sure exactly how complex or differentiating something will turn out to be. But there is still a lot of value in discussing and visualising your beliefs of the complexity and differentiation of each domain.

The following clues can help to assess the complexity and differentiation of each domain. 
 
 - How difficult is it to design a conceptual model for the domain and build (and maintain) it as software? (essential domain complexity)
- Is the current technical solution more complex than it needs to be to provide the current functionality? (accidental technical complexity)
- Are there complex processes, calculations, and decisions happening outside the software? (operational complexity)
- How hard would it be for a new entrant to the market to match or exceed the capability?
- How hard would it be for an existing competitor to match or exceed the capability?
- How much of an advantage is currently produced by the domain (revenue, brand, engagement)?
- How much of an advantage could be produced by domain (revenue, brand, engagement)?
- What damage would occur to the brand if major or recurring failures happened in the domain?
- Which cynefin domain does it fall within?

Complexity can manifest in different forms. Here are some clues for uncovering the essential domain complexity, accidental technical complexity, and operational complexity of each (sub)domain:

- the difficulty in discovering potential value
- designing the rules, logic, and workflows are fundamentally hard to get right
- simpler rules and logic but operating at large scale
- high levels of differentiation are needed to displace existing market leaders or in saturated markets
- specialist expertise that is difficult and expensive to acquire 


## Examples

Check out the [Examples](/examples) to get a better understanding of these charts.

Please feel free to create a pull request with your own examples.

## Additional Resources

- [Core Domain Patterns](https://medium.com/nick-tune-tech-strategy-blog/core-domain-patterns-941f89446af5)

- [Visualising Sociotechnical Architecture with DDD and Team Topologies](https://medium.com/nick-tune-tech-strategy-blog/visualising-sociotechnical-architecture-with-ddd-and-team-topologies-48c6be036c40)

## Contributors

Thanks to all [existing and future contributors](https://github.com/ddd-crew/core-domain-charts/graphs/contributors) and to [Eduardo da Silva](https://twitter.com/emgsilva) who has contributed to the Core Domain Chart:

The Core Domain Chart was inspired heavily by:

- [Wardley Mapping](https://medium.com/wardleymaps)
- [Team Topologies](https://teamtopologies.com/)

## Contributions, Questions and Feedback

The Core Domain Chart is freely available for you to use. In addition, your feedback and ideas are welcome to improve it or to create new versions.

If you have questions you can ping us or open an [Issue](https://github.com/ddd-crew/core-domain-charts/issues/new/choose).

Feel free to also send us a pull request with your examples.

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
