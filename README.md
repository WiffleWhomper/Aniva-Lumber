# Aniva-Lumber
Custom Structure JSON Files For Console and PC Instructions ONLY WORKS ON DAYZ 1.26 AND LATER!!! NOT EARLIER VERSIONS!!!

"  - A strategic Last attempt to hold-off the inevitable. As the zombie infestation began to take hold of Sakhal, Aniva's industrial district made a last attempt for salvation by ordering in truck loads of materials to be processed to make a barrier between them and the outside world. 
It seems the efforts were in vain. 
Now you stumble across the remaining supplies. 
As their story ended, yours begins.
Welcome to Aniva. "

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

Instructions:

Stop Your Server Ensure your server is offline before proceeding.

Activate cfggameplay.json For console users on Nitrado Servers, go to "General Settings" and tick Enable cfggameplay.json. For PC Servers, add the following line to your serverDZ.cfg:

enableCfgGameplayFile = 1; (Note: For some PC servers, including Nitrado, the serverDZ.cfg may be hidden. To access it, enable "Expert Mode" in your settings, then navigate to "Expert Settings" to find serverDZ.cfg. Remember to stop the server before making changes.)

Upload the JSON File Upload AnivaLumber.json from the extracted files to the "custom" folder within the mission directory on your server. (If a custom folder doesn't exist, create one.)

Edit the cfggameplay.json Open the cfggameplay.json file in the correct mission file for your server and locate the "objectSpawnersArr" line. This tells your server to load your custom file.

Edit the file to look like this:

"objectSpawnersArr": ["custom/AnivaLumber.json"]

If you're already calling other custom JSONs to spawn items or buildings, separate them with commas:

"objectSpawnersArr": ["custom/AnivaLumber.json", "custom/anotherfile.json", "custom/differentfile.json"] 

restart your server and the new lumber file will spawn with all items ready for use.

Thanks, and happy gaming! Created by @WiffleWhomper For support or inquiries: c.lindberg823@gmail.com
