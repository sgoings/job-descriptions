# Software Development Engineer in Test (SDET), Deis

<< common.md >>

## You Might Be

1. A person who doesn't accept the statement: "That could never be automated."
Conversely, you can't stand testing something that could easily be done by a
machine.

2. A contributor who jumps into action when you hear "it works on my machine."
You go the extra mile to implement a solution such that no human ever
experiences that same situation again.

2. A master of sandbox testing. You strive to create disposable environments
in order to ease issue reproduction for anyone on the team. You're not afraid
to get into the code and instrument some test doubles, mocks, and stubs.
You might also get crazy and [mock an entire third party component][mbtest] in
order to coerce the service's dependencies into a bad state.

3. A manager of [chaos monkeys][chaos]. Despite all the work you put into tests that are
exercised before changes get pushed out to production, you understand that a
well trusted and trained simian army is your best ally to uncover hard to
reproduce problems and performance issues.

4. An avid learner. You like keeping abreast on a wide variety of subjects.
Testing is great, but [GTAC][gtac] isn't the only conference you care
about.

## The Duties

The Deis team loves creating components that the open source community at large
can seamlessly plug into their existing toolsets and workflows. In order to
maintain the user experience people have come to expect with the Deis product
offerings, we need someone to help us further refine our:

### 1. Automated Testing

You'll spend most of your time bolstering our unit, functional, and end to end
test suites. You'd be building service mocks for functional tests and using bare
metal and cloud providers such as [Amazon AWS][aws], [Digital Ocean][do],
[Google Container Engine][gke], and [Microsoft Azure][azure] to verify all
components work in harmony. You'll also be getting cozy with the
[Ginkgo BDD testing Framework][ginkgo] and a few Bash testing frameworks like
[bats][bats] and [roundup][roundup].

### 2. CI/CD Systems

You'll jump across a few CI systems like [Travis CI][travis] and
[Jenkins][jenkins] to ensure that the tests you have curated are providing
valuable feedback to the team on every change to the codebase.

### 3. Product Quality Visibility

You'll help build an information radiator that provides a visual representation
of each component's current status, quality history, and runtime performance.
Additionally, it will provide an overarching view of the health of all our
systems.

[aws]: http://aws.amazon.com/
[azure]: https://azure.microsoft.com/en-us/
[bintray]: https://bintray.com/
[deis]: http://deis.io/
[do]: https://digitalocean.com
[docker]: https://www.docker.com/
[dockerhub]: https://hub.docker.com/
[flow]: https://en.wikipedia.org/wiki/Flow_(psychology)
[ginkgo]: http://onsi.github.io/ginkgo/
[gke]: https://cloud.google.com/container-engine/
[gtac]: https://developers.google.com/google-test-automation-conference/
[glide]: https://github.com/Masterminds/glide
[glide]: https://github.com/Masterminds/glide
[helm]: http://helm.sh/
[jenkins]: https://ci.deis.io
[joelux]: http://www.joelonsoftware.com/uibook/chapters/fog0000000062.html
[kubernetes]: http://kubernetes.io/
[quay]: https://quay.io/
[rigger]: https://github.com/deis/rigger
[terraform]: https://www.terraform.io/
[travis]: https://travis-ci.org/deis
[wercker]: http://wercker.com/
[bats]: https://github.com/sstephenson/bats
[roundup]: http://bmizerany.github.io/roundup/
[chaos]: https://github.com/Netflix/SimianArmy
[mbtest]: http://www.mbtest.org/
