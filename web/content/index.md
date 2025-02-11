+++
template = "index.html"
+++

LATTE is an [ASPLOS][] workshop on applying programming languages and compilers
techniques to generate hardware accelerators.
The workshop will take place on **April 15, 2021** and will feature 23 papers
along with 2 keynote presentations.
The [call for participation](./cfp) has been archived.
Read [Rachit's blog post][pl-blog] summarizing the work in this area and advertising the workshop.
Please register for it through the [ASPLOS registration website][asplos-registration].

## Program

The LATTE program will consist of sessions of 2-3 papers each grouped according
to their theme.
Each paper talk will be 6 minutes long and prerecorded.
After the talk, we will spend 6 minutes in small breakout rooms discussion the
session papers.
After that, we will regroup in the main session and dedicate 6 minutes for
plenary questions to the authors.
All talks will be released a few days before the workshop.

To enable extensive discussions, each paper will have [Github discussion
thread][github-thread].
Authors will be subscribed to the thread for their paper and will answer questions
during and (hopefully) after the workshop!

| Time (EST) | Event |
|-------------|-------|
| 10am - 10.15am | Opening & Introductions |
| 10.15am - 11am | [Keynote - Sharad Malik][sharad-position] |
| 11am - 11.30am | [Session 1 - Formal](#formal) |
| 11.30am - 12pm| [Session 2 - Language Design](#language-design) |
| 12pm - 12.15pm|Break |
| 12.15pm - 12.45pm| [Session 3 - HDL](#hdl) |
| 12.45pm - 1.15pm| [Session 4 - Interconnect & Memory](#interconnect-memory) |
| 1.15pm - 2.00pm| Lunch Break |
| 2.00pm - 2.30pm|Topic Discussion |
| 2.30pm - 3.00pm| [Session 5 - Integration](#integration) |
| 3.00pm - 3.45pm|Keynote - Sophia Yakun Shao |
| 3.45pm - 4.00pm| [Session 6 - HLS](#hls) |
| 4.00pm - 4.15pm|Break |
| 4.15pm - 4.45pm| [Session 7 - Industrial & Applications](#industrial-applications) |
| 4.45pm - 5.15pm| [Session 8 - Abstractions](#abstractions) |
| 5.15pm - 5.45pm|Closing Discussion |

## Discussion Topics

We will have 1-2 short discussion sessions that will feature a debate
among the attendees.
We need your help building a list of controversial topics to serve as grist for
the discussion mill.

Please submit a sentence or two about an open problem, philosophical question,
or other thought you'd like to see discussed at the workshop.
You can submit as many of these as you like.
We'll use these suggestions to set up a debate during the workshop.

Add your topic suggestions by editing [this wiki page][topics] on GitHub.

## Keynotes

- **[Sharad Malik][sharad]**: [Hardware-Software Interface Specification for Verification in Accelerator-Rich Platforms][sharad-position]
- **[Yakun Sophia Shao][sophia]**: Efficient and Productive: Holistic Approach to Accelerator Design, Integration, and Scheduling

## Accepted Papers

The LATTE 21 program will feature the following 23 papers and will be discussed
using [SNAPL][]'s round-table discussion format.
Papers are grouped based on a theme.
Each session will start with all papers of a theme and follow with the
discussions.
The camera-ready version for each paper is linked here.
A few days before the workshop, we will link the prerecorded talks for each
paper as well as the [Github discussion][github-thread] for each paper.

{{ program() }}

<div class="committee">
<div class="pc">

### Program Committee

- Thomas Bourgeat, MIT
- Ross Daly, Stanford
- [David Durst](https://davidbdurst.com/), Stanford
- Tobias Grosser, ETH Zürich
- Shunning Jiang, Cornell
- Lana Josipović, EPFL
- Vinod Kathail, Xilinx
- Chris Leary, Google
- Thierry Moreau, OctoML
- [Clément Pit-Claudel](https://pit-claudel.fr/clement/), MIT
- Jose Renau, UCSC
- Hongbo Rong, Intel
- John Wickerson, ICL

</div>

<div class="organization">

### Organizing Committee

- [Rachit Nigam](https://rachitnigam.com), Cornell University
- [Adrian Sampson](http://adriansampson.net), Cornell University
- Stephen Neuendorffer, Xilinx
- [Zhiru Zhang](https://www.csl.cornell.edu/~zhiruz/), Cornell University

</div>

</div>


[topics]: https://github.com/cucapra/latte20/edit/main/discussion.md
[snapl]: http://cs.brown.edu/~sk/Memos/Conference-Discussion-Format/
[sigplanconf]: http://www.sigplan.org/Resources/Author/
[hotcrp]: https://latte.cs.cornell.edu/
[asplos]: https://asplos-conference.org
[pl-blog]: https://blog.sigplan.org/2021/02/17/languages-tools-and-techniques-for-accelerator-design/
[sophia]: https://people.eecs.berkeley.edu/~ysshao/index.html
[sharad]: https://www.princeton.edu/~sharad/
[github-thread]: https://github.com/cucapra/latte21/discussions/categories/papers
[sharad-position]: /paper/6.pdf
[asplos-registration]: https://web.cvent.com/event/6259afee-6594-4456-86a0-2a22fbfc47b8/summary
