# LearnGraphicsProgramming optional English resources

This public repository distributes only eight optional English Misaki neural
resources, their checksums, provenance and upstream license notices. It contains
no LearnGraphicsProgramming application source, APKs, shared Kokoro acoustic
model, voice weights, training corpora or Python runtime.

Download the individual ONNX/JSON files from the versioned
[English Misaki FP32 v1 release](https://github.com/SimDynamics/LearnGraphicsProgramming-Resources/releases/tag/english-misaki-fp32-v1).
Exact file sizes, SHA-256 digests and HTTPS URLs are in [catalog.json](catalog.json).
The eight model/configuration files total **12,915,892 bytes**. This distribution
preserves their original validated bytes, full FP32 precision and model behavior;
no quantization, retraining or replacement model is used.

The US and GB BART exports derive from Peter Reid's Apache-2.0 models. The spaCy
tok2vec/tagger export and frontend derive from Explosion's MIT-licensed model,
spaCy, Thinc and normalization lookups. Each model retains its own upstream
license; there is no claim of ownership or endorsement by those authors.
See [provenance.json](provenance.json) for pinned source revisions and original
weight hashes and [licenses/NOTICE.txt](licenses/NOTICE.txt) for modifications,
copyrights, included license texts and attribution. Commercial redistribution
is subject to those retained Apache-2.0 and MIT obligations. Training corpora,
WordNet and the lemmatizer are not included in this POS-only conversion.

The app downloads individual files only after the user requests installation,
then validates the pinned length and SHA-256 before private-storage installation.
Versioned release files must not be replaced with different bytes; new model
versions require a new release and checksum contract.
