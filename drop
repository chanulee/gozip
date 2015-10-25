on open the_Droppings
	set dropped_Files to {}
	set dropped_Folders to {}
	repeat with a_Drop in the_Droppings
		if folder of (info for a_Drop) then
			set end of dropped_Folders to a_Drop
		else
			set end of dropped_Files to a_Drop
		end if
	end repeat
	display dialog "You dropped " & (dropped_Files's length) & " files, and " & (dropped_Folders's length) & " folders just now."
end open
