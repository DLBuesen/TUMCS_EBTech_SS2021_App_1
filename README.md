# TUMCS_EBTech_SS2021_App_1
- Cyclic voltammetry simulation of mediated enzymatic catalysis in solution.

# System Description Highlights
- Simulation of the experimental cyclic voltammogram signal for a given set of dimensional parameters (concentrations, diffusion rates, catalytic rate constants, etc).
- Redox enzymatic catalysis mediated by a redox mediator.
- Reversible electron transfer at the electrode (Nernst Equation).
- The mechanism is a ping-pong mechanism with allowance for enyzme inhibition, as described in the following research [paper](https://pubs.acs.org/doi/abs/10.1021/ja204637d). Additional research papers which are relevant for gaining an understanding of the system and the numerical simulation of cyclic voltammograms are listed in a separate section below.

# How the App can be Useful
- To simulate the predicted experimental signals for a given set of experimental conditions and dimensional parameters.
- To explore how the qualitative features of cyclic voltammograms change depending on various conditions.
- To explore how secondary plots (i.e. plots based on peak currents) can be affected by these changes.

# Typical Workflow and Results
- Start the app by using the shortcut and by running as administrator.
- When starting the app, the location of the parameter and data export files must be confirmed. This only needs to be done once per session.
- The simulation is then performed by pressing a button in the main menu.
- A plot of the cyclic voltammogram appears. Tools within the graph can be used to read the data points, or to save the figure as a .png.
- The current-potential data for the simulated CV is saved to the data export excel file. The data can then be transferred to another spreadsheet or graphing program (i.e. Origin) for reformatting or for making overlay plots.
- The program is closed by closing the main window of the simulation.
- A tour of the app (deployed via Docker container) is shown in a video for the [windows 10](https://vimeo.com/538415217), ignore anything in this video related to docker, XLaunch, etc. This video is only for showing the main features of the app.

# Operating Systems and Installation
- The app can be run only from Windows 10.
- Download the project folder from here, extract it to the desktop.
- Run the installer as administrator with the defaults. It is a standard windows installation which does not have any additional prerequisites. It is not containerized and therefore does not require permissions to access the screen (i.e. no Docker, XLaunch, etc.).
- Create a separate folder for the app launch and for your data on the desktop. Place a copy of the Parameters folder there as well as links to the app launch icon and to the data export excel file. If these steps are not done, then the app will not work because the app is installed in the applications folder, where limited read/write accesss is granted.
- The details can be seen in a demonstration video provided [here] (reference).
- Additional installation instructions which are operating system specific can be found within this project for [Windows 10](https://github.com/DLBuesen/cv_sim_mediated_in_soln/tree/main/windows10) and for [Ubuntu 18.04](https://github.com/DLBuesen/cv_sim_mediated_in_soln/tree/main/ubuntu1804).

# License
- This app was made using Matlab with an education and research license. Therefore, use of the app must be within the scope of this license.
- Although this app is currently being used for a lecture course at TUMCS, it is not restricted to this purpose only.

# Some Additional Reference Articles
- [New insights into the enzymic catalysis of the oxidation of glucose by native and recombinant glucose oxidase mediated by electrochemically generated one-electron redox cosubstrates.](https://pubs.acs.org/doi/abs/10.1021/ja00054a001)

- [Kinetic control by the substrate and the cosubstrate in electrochemically monitored redox enzymatic immobilized systems. Catalytic responses in cyclic voltammetry and steady state techniques](https://www.sciencedirect.com/science/article/abs/pii/S0022072802006587)

- [Electrochemistry of Immobilized Redox Enzymes:  Kinetic Characteristics of NADH Oxidation Catalysis at Diaphorase Monolayers Affinity Immobilized on Electrodes.](https://doi.org/10.1021/ja0569196)

- [Cyclic Voltammetric Simulation for Electrochemically Mediated Enzyme Reaction and Determination of Enzyme Kinetic Constants](https://doi.org/10.1021/ac9711807)

- [Extracting kinetic parameters for homogeneous ... mediated enzyme reactions from cyclic voltammetry and simulations](https://doi.org/10.1016/j.bioelechem.2008.08.001)

- [A Numerical Approach to Modeling the Catalytic Voltammetry of Surface-Confined Redox Enzymes](https://doi.org/10.1021/jp047808g)
