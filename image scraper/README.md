## Setup:

1. Open command prompt
2. Clone this repository (or [download](link))
   ```
   git clone
   ```
3. Install Dependencies
   ```
   pip install -r requirements.txt
   ```
4. Edit your desired parameters in main.py
   ```
   search_keys         = Strings that will be searched for
   number of images    = Desired number of images
   headless            = Chrome GUI behaviour. If True, there will be no GUI
   min_resolution      = Minimum desired image resolution
   max_resolution      = Maximum desired image resolution
   max_missed          = Maximum number of failed image grabs before program terminates. Increase this number to ensure large queries do not exit.
   number_of_workers   = Number of sectioned jobs created. Restricted to one worker per search term and thread.
   ```
5. Run the program
   ```
   python main.py
   ```
