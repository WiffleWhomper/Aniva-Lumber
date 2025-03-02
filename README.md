# Aniva-Lumber
Custom Structure JSON Files For Console and PC Instructions ONLY WORKS ON DAYZ 1.26 AND LATER!!! NOT EARLIER VERSIONS!!!

A strategic stronghold that seen the re-utilization of Aniva's industrial compoud during troubling times in the hopes of creating a highly defended position. As the inhabitants obtained material and began trimming it down, Hell broke loose and their efforts were in vein. Perhaps you can find the supplies and resources they've gathered. Use them to build your own home, or live off the material and lay low as you survive in secret. the choice is yours.

Limited testing was conducted on Xbox Series S using DayZ Version 1.26 as of March 2025.

Created by @WiffleWhomper. For bug reports or issues, please email c.lindberg823@gmail.com with relevant screenshots.

If you'd like to any file, simply load the file into the DayZ Editor.

TERMS OF USE THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded JSON files and instructions could break the functioning of your DAYZ server, requiring a reinstall that would wipe all player progress.

Using these modded files necessitates increased regular restarts to prevent server crashing.

It is strongly recommended that you thoroughly test your server after applying these files to ensure the proper functioning of your server.

I always recommend validating your files at:

https://www.xmlvalidation.com/

https://jsonlint.com/

Instructions: Download the Files Click the "Code" button and select "Download ZIP" from the GitHub Repository. Extract the files to your local PC.

Stop Your Server Ensure your server is offline before proceeding.

Activate cfggameplay.json For console users on Nitrado Servers, go to "General Settings" and tick Enable cfggameplay.json. For PC Servers, add the following line to your serverDZ.cfg:

enableCfgGameplayFile = 1; (Note: For some PC servers, including Nitrado, the serverDZ.cfg may be hidden. To access it, enable "Expert Mode" in your settings, then navigate to "Expert Settings" to find serverDZ.cfg. Remember to stop the server before making changes.)

Upload the JSON File Upload AnivaLumber.json from the extracted files to the "custom" folder within the mission directory on your server. (If a custom folder doesn't exist, create one.)

Edit the cfggameplay.json Open the cfggameplay.json file in the correct mission file for your server and locate the "objectSpawnersArr" line. This tells your server to load your custom file.

Edit the file to look like this:

"objectSpawnersArr": ["custom/AnivaLumber.json"] If you're already calling other custom JSONs to spawn items or buildings, separate them with commas:

"objectSpawnersArr": ["custom/AnivaLumber.json", "custom/anotherfile.json", "custom/differentfile.json"] Restart Your Server After completing these steps, restart your server, and the new store will spawn with all items ready for use.

Thanks, and happy gaming! Created by @WiffleWhomper For support or inquiries: c.lindberg823@gmail.com
