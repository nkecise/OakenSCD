# Introduction
OakenSCD is a Qt-based, professional SCL viewer designed to run on Windows 7 and above. As a portable (no‑install) application, it does not modify system settings or require installation. After downloading, start the application by double‑clicking OakenSCD.exe.

## Fast Loading
Unlike ordinary text files, SCL files are self‑describing XML documents and are often large. To handle this, OakenSCD is implemented in C++ for maximum runtime efficiency and uses file‑slicing combined with multithreaded parsing to analyze the file in parallel. These optimizations enable rapid loading and parsing of large SCL files while keeping resource usage to a minimum.

## Provides both graphical and source views

- **Communication View**

    Presents the station network topology and IED mounting/placement status using a graphical visualization.

- **Source View**

    Displays the selected SCL file as structured text, with support for node folding, search, tagging and so on.

## Comprehensive IED Analysis
- **Basic Information Page**

    Displays configuration details such as version, services, and descriptions.

- **Graphical View Page**

    Visualizes relationships between IEDs based on Inputs. Hovering over a link highlights the connection; clicking displays detailed terminal connection information.

- **Dataset Page**

    Displays dataset details.

- **GSE/SV Control Blocks**

    Displays GSE/SV control blocks and their associated dataset details.

- **GOOSE/SMV Inputs Page**

    Shows GOOSE/SMV Inputs details organized hierarchically by IED / DataSet / DOI.

- **Report/Log Control Blocks**

    Displays detailed information about Report and Log control blocks.

## How to use
You can watch a short walkthrough video that demonstrates the main features and typical workflows.



https://github.com/user-attachments/assets/3b56ea29-afcd-4918-bb6d-810e1796bdaf



Alternatively, download the MP4 and play it locally with your preferred video player.

