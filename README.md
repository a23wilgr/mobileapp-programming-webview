
# Rapport

Namn på appen har ändrats, internet-access och JavaScript har aktiverats. 
WebView har skapats för att kunna visa internal och external sidorna. Den externa visar högskolans hemsida,
och den interna visar en egengjord HTML-fil. Dessa två kallas sedan på i två funktioner, en funktion
för externa och den andra för interna, med hjälp av JavaScript.

Kodexempel
Funktioner som kallar på showInternalWebPage, det ser likadant ut för showExternalWebPage:
        if (id == R.id.action_internal_web) {
            Log.d("==>","Will display internal web page");
            showInternalWebPage();
            return true;
        }

Programkoden som funktionen kallar på, internal som exempel:
        public void showInternalWebPage(){
            myWebView.loadUrl("file:///android_asset/about.html");
        }


Screenshots på internal och external
![](Internal_screenshot.png)
![](External_screenshot.png)


Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
