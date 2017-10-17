# scikit-learn-kills-pants
A demonstration of pants failing to build a pex using scikitlearn

To reproduce, run `PEX_VERBOSE=5 ./pants binary awesome-code:awesome-app`, which results in the [log here](../master/verbose-output)
