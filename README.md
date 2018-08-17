# Neural Network Theories

A summary and Python TensorFlow implementation of theories described in [Learning Internal Representations by Error Propagation](https://web.stanford.edu/class/psych209a/ReadingsByDate/02_06/PDPVolIChapter8.pdf) by David E. Rumelhart, Geoffrey E. Hinton, and Ronald J. Williams.

---

### A Brief HIstory

In their book, _Perceptrons_ (1969), Marvin Minsky and Seymour Papert state:

> The perceptron has shown itself worthy of study despite (and even because of!) its severe limitations. It has many features that attract attention: its linearity; its intriguing learning theorem; its clear paradigmatic simplicity as a kind of parallel computation. There is no reason to suppose that any of these virtues carry over to the many-layered version. Nevertheless, we consider it to be an important research problem to elucidate (or reject) our intuitive judgement that the extension is sterile. Perhaps some powerful convergence theorem will be discovered, or some profound reason for the failure to produce an interesting "learning theorem" for the multilayered machine will be found. (pp. 231-232)

Such pessimistic view presented by Minsky and Papert (1969) arguably brought about the so-called _AI winter_ which lasted throughout the following decade.

In this report published in 1985, Rumelhart, Hinton, and Williams conclude:

> Although our learning results do not *guarantee* that we can find a solution for all solvable problems, our analyses and results have shown that as a practical matter, the error propagation scheme leads to solutions in virtually every case.

Through persistence in the shadow of doubt, the trio of academics answered Minsky and Papert's challenge, and ignited a renewed interest in deep learning. Today, these very models are ubiquitous. From computer processor optimization (e.g. [AMD SenseMI](https://www.amd.com/en/technologies/sense-mi)) to impeccable text-to-speech synthesis (e.g. [Google Tacotron](https://ai.googleblog.com/2018/03/expressive-speech-synthesis-with.html), [Google Duplex](https://ai.googleblog.com/2018/05/duplex-ai-system-for-natural-conversation.html)), neural networks are now the face of artificial intelligence.

---

### Table of Contents

- [0. Introduction](0.%20Introduction)
- [1. The XOR Problem](1.%20The%20XOR%20Problem)
- [2. Parity](2.%20Parity)
- [3. The Encoding Problem](3.%20The%20Encoding%20Problem)
- [4. Symmetry](4.%20Symmetry)
- [5. Addition](5.%20Addition)
- [6. The Negation Problem](6.%20The%20Negation%20Problem)
- [7. The T-C Problem](7.%20The%20T-C%20Problem)
- [8. Recurrent Nets](8.%20Recurrent%20Nets)

---

### Required Python Libraries

	matplotlib
	numpy
	tensorflow
