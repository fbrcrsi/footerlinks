# footerlinks
Add custom links on the footer of phpBB 3.1.3 forum 

## Quick Install
You can install this on the latest release of phpBB 3.1.3 by following the steps below:

1. [Download the latest release](https://github.com/fbrcrsi/footerlinks).
2. Unzip the downloaded release, and change the name of the folder to `footerlinks`.
3. In the `ext` directory of your phpBB board, create a new directory named `fbrcrsi` (if it does not already exist). 
4. Copy the `footerlinks` folder to `ext/fbrcrsi/` directory of your phpBB board.
5. To configure, edit `/ext/fbrcrsi/footerlinks/styles/all/template/event/overall_footer_copyright_append.html` and edit your links after the line <!-- Edite your links after -->
6. Navigate in the ACP to `Customise -> Manage extensions`.
7. Look for `Footer Links` under the Disabled Extensions list, and click its `Enable` link.

## Uninstall

1. Navigate in the ACP to `Customise -> Extension Management -> Extensions`.
2. Look for `Footer Links` under the Enabled Extensions list, and click its `Disable` link.
3. To permanently uninstall, click `Delete Data` and then delete the `/ext/fbrcrsi/footerlinks` directory.
