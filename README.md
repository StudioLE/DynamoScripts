# Dynamo Scipts from StudioLE

A compilation of potentially useful [Dynamo Scripts](http://dynamobim.org/) to enhance [Autodesk Revit](https://www.autodesk.com/products/revit/overview).

## CO Check

*An automated tool for checking brick co-ordinating sizes.*

Select a dimension element within a Revit project and CO Check will calculate which are accurate brick co-ordinating (CO-, CO, and CO+) sizes.

Where dimensions aren't valid CO sizes it will suggest what you should change them to.

### Usage

CO Check is incredibly easy to use, first follow the download & install instructions below then follow these steps to use the tool.

![CO Check Example](https://raw.githubusercontent.com/StudioLE/DynamoScripts/master/Examples/Screenshots/CO%20Check%20Example%2001.gif)

1) Open `Dynamo Player` within Revit and press the `Run script` icon next to CO Check.

2) After a brief pause a dialog box will appear asking you to select a dimension element. After selecting a dimension, press continue.

3) Another dialog will appear with a summary of which dimensions aren't valid co-ordinating dimensions and suggestions of the closest valid values you could use instead.

4) At the bottom of this dialog is an option to `Set text below dimension to` ensure that `CO Status` is selected and press continue.

5) The status of each dimension will now be shown beneath the value.

6) Running the script a couple more times will enable you to co-ordinate the changes needed to fix the CO sizing like so:

![CO Check Example](https://raw.githubusercontent.com/StudioLE/DynamoScripts/master/Examples/Screenshots/CO%20Check%20Example%2002.gif)

7) If you wish to clear the CO Status from below the dimension just re-run the script but select the `Empty` option instead of `CO Status` when prompted to `Set text below dimension to`. 

### Download & Install

1) The scripts require a couple of Dynamo packages (`Rhythm` and `Data-Shapes`) to function, these are easily installed from within Dynamo, so open up Revit, load an existing file or a new document then go to the `Manage` tab where you'll find the `Dynamo` under `Visual Programming`. Once it has loaded click `Packages` on the menu bar then `Search for a Package..`. Give it a few seconds to synchronise with the server then search for `Rhythm` and press the large download arrow to install the latest version.

2) Once that package is installed search for `Data-Shapes` and install that. You're now free to close Dynamo.

3) Next, either download the dynamo script you need individually or download all the scripts and examples as a [zip archive](https://github.com/StudioLE/DynamoScripts/archive/master.zip).

4) Then extract the zip or copy the individual script to a suitable directory on your computer.

5) Within Revit go to the `Manage` tab where you'll find the `Dynamo Player` under `Visual Programming`. In the Dynamo Player click the `Browse to folder` icon and locate the directory you've saved the scripts to.

6) The scripts should now be loaded and ready to use. Just hit the `Run script` icon to use them.

## Contributing

I'm always on the look out for collaborators so feel free to get in touch, suggest new features, or just fork the repository to add your own families at will.
