# Pass-value-from-html-input-tag-to-asp-textbox
Pass value from html input tag to asp textbox

This is an example instruction hint if such task need to do..

GridViewmbd.Rows[0].Cells[0].Text = GridViewmbd.Rows[0].Cells[0].Text.Replace("VF"+ri, "<input id='VF"+ri+ "' name='VF" + ri + "' runat='server' type='text'></input>");
(GridViewmb.Rows[0].FindControl("etxt")as TextBox).Text= Page.Request.Form["VF0"];
