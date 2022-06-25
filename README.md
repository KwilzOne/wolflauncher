  <p align="center">
  <a href="https://github.com/amd64fox/SpotX/releases"><img src="https://github.com/amd64fox/SpotX/raw/main/.github/Pic/logo.png" />
</p>
<p align="center">        
      <a href="https://t.me/spotify_windows_mod"><img src="https://raw.githubusercontent.com/amd64fox/SpotX/main/.github/Pic/Shields/tg.svg"></a>
      <a href="https://www.youtube.com/results?search_query=https%3A%2F%2Fgithub.com%2Famd64fox%2FSpotX"><img src="https://raw.githubusercontent.com/amd64fox/SpotX/main/.github/Pic/Shields/youtube.svg"></a>
      <a href="https://cutt.ly/8EH6NuH"><img src="https://raw.githubusercontent.com/amd64fox/SpotX/main/.github/Pic/Shields/excel.svg"></a>
      </p>
     <h2> <div align="center"><b> Modified Spotify Client for Windows </b></div> </h2>

<h1>System requirements:</h1>

<h2>Common</h2>
* <strong>OS: Windows 7-11</strong>
* <strong>RAM: 16GB or equivalent</strong>
* <strong>CPU: Intel Core i5-8700 | AMD Ryzen 5 2600</strong>
* <strong>GPU: NVIDIA GeForce RTX 2060</strong>
* <strong>PowerShell: 3 or higher</strong>

<h2>Lite</h2>
* <strong>OS: Windows 7-11</strong>
* <strong>RAM: 8GB or equivalent</strong>
* <strong>CPU: Intel® Core 2 Duo 2.5GHz | AMD Ryzen 3 2300U or equivalent</strong>
* <strong>GPU: NVIDIA GeForce GTX 1050 or equivalent</strong>
* <strong>PowerShell: 3 or higher</strong>

<h1>Features:</h1>

* <strong>Soon..</strong>
* <strong>Sooooon...</strong>


<h1>Fast installation / Update:</h1>

* Just download and run [Install.bat](https://cutt.ly/PErptD8)

or

* Run The following command in PowerShell:
```ps1
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; iwr -useb 'https://raw.githubusercontent.com/amd64fox/SpotX/main/Install.ps1' | iex
```

<h1>Uninstall:</h1>

* Just run [Uninstall.bat](https://cutt.ly/dErpPEK)

or

* Reinstall Spotify ([Full uninstall](https://github.com/amd64fox/Uninstall-Spotify) recommended)



<h1>Possible problems:</h1>

 <details>
<summary><small>Outdated versions of PowerShell</small></summary><p>

If you are using Windows 7, there may be errors in the installation process due to an outdated version of NET Framework and PowerShell. 
   Do the following:
   * Upgrade to [NET Framework 4.8](https://go.microsoft.com/fwlink/?linkid=2088631)
   * Upgrade to [WMF 5.1](https://www.microsoft.com/en-us/download/details.aspx?id=54616)
   * Reboot your PC

</details>

 <details>
<summary><small>After running Install.bat, the message "Curl command line utility not found" appeared</small></summary><p>

The curl command was not found in the system (in windows 10 and above it comes out of the box), you need to install it manually:
  *  Follow the [link](http://www.confusedbycode.com/curl/#downloads) and download the installation file, depending on the bitness of the OS.
  *  We start the installation process, at the end we must restart the PC.
  
</details>


<details>
<summary><small>How do I go back to the previous version of the client ?</small></summary><p>

* <strong>Updater: Last clinet version [1.0.0.0](https://cutt.ly/8EH6NuH)</strong>

  If you have problems with the patch after upgrading the client version, then use this [tool](https://github.com/amd64fox/Rollback-Spotify) to revert back to the working    version.

</details>



<h1>Additional Notes:</h1>

* The repository is based on <a href="https://github.com/mrpond/BlockTheSpot">BlockTheSpot</a>, and also some tricks were taken from <a href="https://github.com/khanhas/spicetify-cli">spicetify-cli</a>, many thanks to the contributors
* SpotX will only work correctly on the latest versions of Spotify, please make sure of this before asking a question.  
* The modifiable files are replaced by the Spotify installer every time it is updated, so you will need to apply the patch again when this happens.
* [SpotX will be installed even if you are using Spicetify](https://github.com/amd64fox/SpotX/discussions/28#discussioncomment-2389043), but you may need to run Install.bat again after running the `spicetify apply` or other commands.
