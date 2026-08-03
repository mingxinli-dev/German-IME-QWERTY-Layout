# German IME (QWERTY Layout)

## What is this IME?
This IME (Input Method Editor) allows you to type German characters and basic punctuation marks using a standard US QWERTY keyboard layout.

## Platform Support
This IME is currently only available on **Windows**.

## How to Install and Use
Depending on your needs, you can choose one of the following options:

* **Use the Pre-built Version (Recommended):**
  1. Open the `deutsch` folder and run `Setup.exe`.
  2. Follow the installation wizard. 
  3. Once installed, the layout should appear in your Windows keyboard settings. (If it doesn't appear immediately, try restarting your computer or adding it manually via **Settings > Time & Language > Language & Region**).

* **Customize Your Own Version:**
  If you wish to modify key bindings or change the layout description, download [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134) and open the source file `deutsch.klc`.

## Key Combinations & Usage
> **Prerequisite:** A physical keyboard with a **US QWERTY** layout is strongly recommended. Similar layouts (such as UK QWERTY) should also work fine.

This layout retains the standard US QWERTY arrangement for regular English letters and symbols, while adding support for German special characters, currency signs, and typographic symbols using **AltGr** (Right `Alt` or `Ctrl` + `Alt`).

### 1. German Letters
To input German umlauts and Sharp S, use `AltGr` or `AltGr + Shift`:

| Target Character | Description | Key Combination |
| :--- | :--- | :--- |
| **ä** | Small A with Diaeresis | `AltGr` + `A` |
| **Ä** | Capital A with Diaeresis | `AltGr` + `Shift` + `A` |
| **ö** | Small O with Diaeresis | `AltGr` + `O` |
| **Ö** | Capital O with Diaeresis | `AltGr` + `Shift` + `O` |
| **ü** | Small U with Diaeresis | `AltGr` + `U` |
| **Ü** | Capital U with Diaeresis | `AltGr` + `Shift` + `U` |
| **ß** | Small Sharp S (Eszett) | `AltGr` + `S` |
| **ẞ** | Capital Sharp S | `AltGr` + `Shift` + `S` |

---

### 2. Accented Letters & Dead Keys
The Single Quote/Apostrophe key (`'`) serves as a **dead key** when combined with `AltGr`:

* **Acute Accent (`é` / `É`):** Press `AltGr` + `'`, release, then press `e` or `E`.
  * `AltGr` + `'` $\rightarrow$ `e` = **é**
  * `AltGr` + `'` $\rightarrow$ `Shift` + `E` = **É**

---

### 3. Symbols & Punctuation

#### Currency & Numbers
| Output | Description | Key Combination |
| :---: | :--- | :--- |
| **€** | Euro Sign | `AltGr` + `E` *or* `AltGr` + `4` |
| **¥** | Yen Sign | `AltGr` + `Y` |
| **£** | Pound Sign | `AltGr` + `L` |
| **²** | Superscript 2 | `AltGr` + `2` |
| **³** | Superscript 3 | `AltGr` + `3` |
| **‰** | Per Mille Sign | `AltGr` + `5` |
| **°** | Degree Sign | `AltGr` + `G` |

#### Quotation Marks & Typographic Symbols
| Output | Description | Key Combination |
| :---: | :--- | :--- |
| **§** | Section Sign | `AltGr` + `P` |
| **§§** | Double Section Sign (Ligature) | `AltGr` + `Shift` + `P` |
| **„** | German Double Low Quote | `AltGr` + `[` |
| **‚** | German Single Low Quote | `AltGr` + `Shift` + `[` |
| **“** | Left Double Quote | `AltGr` + `]` |
| **‘** | Left Single Quote | `AltGr` + `Shift` + `]` |
| **«** | Left Guillemet | `AltGr` + `Shift` + `,` |
| **»** | Right Guillemet | `AltGr` + `Shift` + `.` |
| **–** | En Dash | `AltGr` + `N` |
| **—** | Em Dash | `AltGr` + `M` |
| **…** | Ellipsis | `AltGr` + `.` |

#### Special Spaces
* **Non-Breaking Space:** `AltGr` + `Space`
* **Narrow Non-Breaking Space:** `AltGr` + `Shift` + `Space`

## License
This project is licensed under the [MIT License](LICENSE).