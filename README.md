# Test Websites for Same-Origin Policy and Agentic Browser Security Experiments

This repository contains test websites used in 
the experiments described in the following paper:

@inproceedings{roesner_kohlbrenner_2026_agentic_sop,
  title={Agentic Browsers and the Same-Origin Policy},
  author={Roesner, Franziska and Kohlbrenner, David},
  booktitle={Agents in the Wild Workshop @ ICLR},
  year={2026}
}

More information at: https://agent-security.cs.washington.edu. 

These websites must be hosted on two separate domains for 
testing. In this repository, we have replaced the domains 
with generic placeholders `A.com` and `B.com` -- these must 
be replaced with real domains hosting the websites for them
to function correctly.

The prompts used to test agentic browsers on these websites
are included in full in the paper.

## Website Summaries

`A.com`
* `bob1.html` : Used for additional experiments in Section 4.3
* `bob2.html` : Used for additional experiments in Section 4.3
* `complexpage.php` : Used as described in Appendix A
* `cookie.php` : Used to set cookie for personalized content tests
* `inner.html` : Used as described in Appendix A
* `input.html` : Used as described in Appendix A
* `input2.html` : Used as described in Appendix A
* `other.html` : Used as described in Appendix A
* `outer-cross.html` : Used as described in Appendix A
* `outer-same.html` : Used as described in Appendix A
* `poc.html` : Used for proof-of-concept cross-origin outer-from-inner-frame data theft
* `poc2.html` : Variant of `poc.html` which attempts a full prompt injection
* `poc3-frame.html` : Used with `B.com/poc3.html`
* `poc4-frame.html` : Used with `B.com/poc4.html`
* `summary.php` : Form submission destination for proofs-of-concept

`B.com`
* `bob1.html` : Used for additional experiments in Section 4.3
* `bob2.html` : Used for additional experiments in Section 4.3
* `inner.html` : Used as described in Appendix A
* `other.html` : Used as described in Appendix A
* `poc3.html` : Used for proof-of-concept cross-origin inner-from-outer-frame data theft
* `poc4.html` : Used for proof-of-concept JavaScript injection attack
* `summary.php` : Form submission destination for proofs-of-concept
