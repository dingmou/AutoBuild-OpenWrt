# AutoBuild-OpenWrt

Build OpenWrt firware [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) using GitHub Actions  
Hereby thank P3TERX for his amazing job: https://github.com/P3TERX/Actions-OpenWrt/

## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/esirplayground/AutoBuild-OpenWrt)
- Click [.github/workflows] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- In 'Lede' path,input''./scripts/diffconfig.sh>diffconfig'. 
- Via vi open file 'diffconfig',copy the content paster to 'x86_64.config' (instead all of the orign content), commit.
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- Press '2(or other number) contributors'. select your name,press 'Verified'.
- The build starts automatically. Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
- Default Web Admin IP: `192.168.5.1`, username `root`，password `password`
