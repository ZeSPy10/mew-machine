# Mew Machine

ZeSpy10- I have edited the script to automatically get the save file from a USB E: device. It works with Pokemon blue and red.

A Python recreation of the [Mew Machine](#1-what-is-the-mew-machine) software. This script adds a nearly legit YOSHIRA Mew to your save file when you have a open slot in your party.

## Usage

### System requirements:

- Python 3.6+

### Save file requirements:

- A dumped save file from a Pokemon Red or Pokémon Blue game
- An empty slot in your party

### How to download and use it:

1. Clone this repo using the `git clone https://github.com/guilherssousa/mew-machine.git` command.
2. Backup your save file. I don't want to be responsible for any damage to your save file.
3. Run the script using `python main.py <path-to-save-file>`. The python command may be `python3` or `py` depending on your system, and the path to the save file may be relative or absolute.

This will generate a YOSHIRA Mew in your save file party with a random Trainer ID and display a fancy Certificate of Authenticity on your screen.

## FAQ

### 1. What is the Mew Machine?

The **_Special Machine_**, also known as **_Mew Machine_**, was used to distribute event Pokémon in Generation I starting with the Nintendo Space World '97 Mew distribution. It was mainly used to distribute Mew but also other events like Surfing Pikachu.

<img src="https://archives.bulbagarden.net/media/upload/5/5a/Mew_machine.jpg" alt="A Mew Machine" align="right">

### 2. What is the YOSHIRA Mew?

The Mew generated by this script is a nearly identical copy from a legit YOSHIRA Mew, that was distributed firstly at the [Pokémon League Nintendo Training Tour '99](#credits) on October 1999.

The YOSHIRA Mew was distributed in two Mew Machines, and the differences between the two were the OT names they used, "YOSHIRA" and "YOSHIRB" respectively.

The IVs of the YOSHIRA Mew are: IVs: 5 HP, 10 Attack, 1 Defense, 12 Speed, and 5 Special.

The script uses a [YOSHIRA Mew distributed on U.S. Toys "R" Us stores](#credits) from October 8th 1999 to December 12th 1999 as a base to generate a new YOSHIRA Mew with a random Trainer ID.

### 3. Is it a hacked or legit Mew?

The generated Mew is a nearly identical copy from a legit YOSHIRA Mew, so it's a legit Mew with a random Trainer ID. Since it's not a official Nintendo distribution, it's not fully legit, but it's as close as it gets since it's a copy from a legit one. At the end, it's up to you to decide if it's legit or not. I personally consider it 95% legit. The only thing that makes it not fully legit is that it didn't came out of a Mew Machine.

### 4. It works on Pokémon Yellow?

I don't know, I didn't test it. If you want to test it, please let me know if it works or not!

### 5. It works on Gen I Virtual Console Pokémon games?

I tested transfering using PKHeX and it did not worked, so I don't think it will work on the Virtual Console games.

### 6. Can I transfer it to later generations or Pokémon HOME?

You can transfer it to Gen II games and it will still be considered a legit Mew. But you can't transfer it to Gen III games or later, since there is no way to trade from Gen I/II to Gen III games. As a side effect, you can't transfer it to Pokémon HOME either.

## Credits

- Jenn from Reddit, [Deoxyz](https://digiex.net/members/50132/) and the Digiex community for the [Pokemon GEN1 YOSHIRA Mew Red Distribution Cart Save File](https://digiex.net/threads/pokemon-gen1-yoshira-mew-red-distribution-cart-save-download.15327/) used to sample Mew DNA.
- Bulbapedia for the articles on the [Mew Machine](https://bulbapedia.bulbagarden.net/wiki/Special_Machine), the [Pokémon League Nintendo Training Tour '99 Mew](<https://bulbapedia.bulbagarden.net/wiki/List_of_European_language_event_Pok%C3%A9mon_distributions_(Generation_I)#Pok.C3.A9mon_League_Nintendo_Training_Tour_.2799_Mew>), the [U.S. Toys "R" Us Mew](<https://bulbapedia.bulbagarden.net/wiki/List_of_European_language_event_Pok%C3%A9mon_distributions_(Generation_I)#U.S._Toys_.22R.22_Us_Mew>) and the [Save data structure (Generation I)](<https://bulbapedia.bulbagarden.net/wiki/Save_data_structure_(Generation_I)>) and the Mew Machine photo.
- EveryGameEver for the amazing [Ep. 9 - EVERY Gen 1 Event Pokémon Feat. Nintendo Rep Jeremy Hepworth](https://www.youtube.com/watch?v=huiCsOIsHwg) video, that helped me to know more about the Mew Machine events and the YOSHIRA Mew.
