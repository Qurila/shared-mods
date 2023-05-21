# Shared Info Description Parts

Contains text modules for an extended InfoDescription
There are also some minor changes to vanilla texts.


## Use Info Description Parts in your Mod

Take the building blocks for "Demand" and "Supply" and build them into your InfoDescription via [AssetData(XXX) Text].
After each [AssetData(XXX) Text] entry for "Demand" and "Supply", it is best to set your own text blocks assigned with a GUID.


-&#xD;&#xA = Line break

-&lt;b&gt;XXX&lt;/b&gt = XXX are Capitalised 

-&lt;font overrideTextColor="true" color='#edc891'&gt;XXX/font&gt; = XXX becomes coloured

-&lt;img height='24' width='24' src="[AssetData(XXX) Icon]"/&gt; = Icon of XXX is displayed

-[AssetData(XXX) Text] = Text from XXX is displayed

This would be a text block for an input/output.

It is started with the opening of a tag for colouring  
-<Text>&lt;font overrideTextColor="true" color='#edc891'&gt;

Then follows a tag to capitalise the text "1t".
-&lt;b&gt;1t&lt;/b&gt; 

After that comes the entry for displaying an icon(Bread in this case), it is best to put a space after the end of the capitalisation tag.
-&lt;img height='24' width='24' src="[AssetData(1010213) Icon]"/&gt;

Now follows the entry for the name of the product (in this case bread). It is also best to leave a space between the icon and the text.
-[AssetData(1010213) Text]

Now the tag is closed for colouring
-&lt;/font&gt;

At the end, you can add a line break. In this way, the next text block you start would begin directly on a new line.
-&#xD;&#xA;

This is what it looks like when finished.
    <Text>
      <GUID>XXX</GUID>
      <Text>&lt;font overrideTextColor="true" color='#edc891'&gt;&lt;b&gt;1t&lt;/b&gt; &lt;img height='24' width='24' src="[AssetData(1010213) Icon]"/&gt; [AssetData(1010213) Text]&lt;/font&gt;&#xD;&#xA;</Text>
    </Text>

That is one of the text modules.
For the finished InfoDescription, these text blocks are joined together via [AssetData(XXX) Text].

To do this, start with the "Demand" text block that provides this mod.
-<Text>[AssetData(1500300045) Text]

then set a line break, but you can also write this at the beginning of the text block that is to follow "Demand".
-&#xD;&#xA;

Now comes the created text block for the first input
-[AssetData(XXX) Text]

You can now append more text blocks if you want to display several inputs.
-[AssetData(XXX2) Text][AssetData(XXX2) Text][AssetData(XXX3) Text]

The following is the "supply" text block provided by this mod. Either place 2 line breaks bevor this to create a line space, or place them at the end of the last text block before "Supply".
-&#xD;&#xA;&#xD;&#xA;[AssetData(1500300046) Text]

After this, you also set a line break, if you have not written it in the first text block after "Supply".
-&#xD;&#xA;

A text block is also used here as after "Demand". Therefore, we use the familiar block here.
-[AssetData(XXX) Text]

In the end, the text for the InfoDescription looks like this
-Text>[AssetData(1500300045) Text]&#xD;&#xA;[AssetData(XXX) Text]&#xD;&#xA;&#xD;&#xA;[AssetData(1500300046) Text][AssetData(XXX) Text]