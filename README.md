# AutoBuild-OpenWrt

Build OpenWrt firware [xiaoqingfeng's Homelede](https://github.com/xiaoqingfengATGH/HomeLede) using GitHub Actions  
Hereby thank P3TERX for his amazing job: https://github.com/P3TERX/Actions-OpenWrt/  https://github.com/esirplayground/AutoBuild-OpenWrt 

## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/esirplayground/AutoBuild-OpenWrt)
- Click [.github/workflows] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- The build starts automatically. Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
- Default Web Admin IP: `192.168.1.1`, username `root`，password `password`
