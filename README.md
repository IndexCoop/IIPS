# IIPs 

Index Improvement Proposals (IIPs) describe standards & upgrades for the Index Coop protocol, including index proposals, protocol upgrades, treasury management, and revisions to the IIP process itself.
 
## Contributing

 1. Review [IIP-0](IIPS/iip-0.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your IIP to your fork of the repository. There is a [template IIP here](iip-X.md).
 4. Submit a Pull Request to SetProtocol's [IIPs repository](https://github.com/set-protocol/IIPS/).

Your first PR should be a first draft of the final YIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new IIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a new thread on [gov.indexcoop.com](https://gov.indexcoop.com/) where people can discuss the IIP as a whole.

If your IIP requires images, the image files should be included in a subdirectory of the `assets` folder for that IIP as follow: `assets/iip-X` (for iip **X**). When linking to an image in the IIP, use relative links such as `../assets/iip-X/image.png`.

When you believe your IIP is mature and ready to progress past the WIP phase, you should ask to have your issue moved into a formal voting phase where it can be ratified or rejected by the community. If the community agrees to include it, the IIP editors will update the state of your IIP to 'Approved'.

## IIP Statuses

* **WIP** - a IIP that is still being developed.
* **Proposed** - a IIP that is ready to be voted on by the community.
* **Approved** - a IIP that has been accepted for implementation by the Index Coop community.
* **Implemented** - a IIP that has been released to mainnet.
* **Rejected** - a IIP that has been rejected.
* **Withdrawn** - a IIP that has been withdrawn by the author(s).
* **Deferred** - a IIP that is pending another IIP/some other change that should be bundled with it together.
* **Moribund** - a IIP that was implemented but is now obsolete and requires no explicit replacement.

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).