<?php
	/////////////////////////////////////////////////////////////////////////
	//                                                                     //
	//                       Created by Jake Hamblin                       //
    //                           jakehamblin.com                           //
	//                                                                     //
	//  FOR ALL THE VALUES, MAKE SURE TO KEEP THE QUOTATIONS AROUND THEM!  //
	//                                                                     //
	/////////////////////////////////////////////////////////////////////////

	/* GENERAL SITE INFORMATION  */
	// Name of your server/community
	$name = "Seth Halsey";

	// Logo of your server/community
	$logo = "images/pfp.jpg";

	// Description of your server/community
	$description = "Description";

	// Discord Guild ID
	$guildid = "GUILDID";

	// Main Color
	$colorhex = "#0f7cff";

	// YouTube video ID (If you don't have/want one, just keep the value empty)
	$youtubeid = "";

	// Background image (Will appear on mobile and if YouTube video isn't defined)
	$backgroundimg = "images/bg.png";

	// Discord invite link
	$discord = "discord";

	// Server IP
	$ip = "sub.yourdomain.tld";

	// Link one
	$link1name = "Link 1";
	$link1 = "#";

	// Link two
	$link2name = "Link 2";
	$link2 = "#";

	// Link three
	$link3name = "Link 3";
	$link3 = "#";

	// Middle link
	$mainbuttonname = "Middle";
	$mainbutton = "#";

	// Link four
	$link4name = "Link 4";
	$link4 = "#";

	// Link five
	$link5name = "Link 5";
	$link5 = "#";

	// Link six
	$link6name = "Link 6";
	$link6 = "#";
	/* END GENERAL SITE INFORMATION */


	/* RANDOM PHP FUNCTIONS AND JOBS */
	// Convert HEX provided to RGB
	list($r, $g, $b) = sscanf($colorhex, "#%02x%02x%02x");
	$colorrgb = $r.", ".$g.", ".$b;

	// Make color darked
	$darkerpercent = ".5";
	$colordarker = $r*$darkerpercent.", ".$g*$darkerpercent.", ".$b*$darkerpercent;

	// Used for navbar links
	$linkarray = array("link1" => "$link1name#$link1", "link2" => "$link2name#$link2", "link3" => "$link3name#$link3", "mainbutton" => "$mainbuttonname#$mainbutton", "link4" => "$link4name#$link4", "link5" => "$link5name#$link5", "link6" => "$link6name#$link6");

	// Discord JSON decode
	$jsonIn = file_get_contents('https://discordapp.com/api/guilds/'.$guildid.'/widget.json');
    $JSON = json_decode($jsonIn, true);
    $membersCount = count($JSON['members']);
?>
