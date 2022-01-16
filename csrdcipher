function csrdcipher(text, key)
    dciphtext = ""
    for l in text
        numl = Int(l)
        dciphnuml = numl - key
        if numl in 65:90
            if dciphnuml < 65
                rotdciphnuml = dciphnuml + 26
                dciphtext = dciphtext * Char(rotdciphnuml)
            else
                dciphtext = dciphtext * Char(dciphnuml)
            end
        elseif numl in 97:122
            if dciphnuml < 97
                rotdciphnuml = dciphnuml + 26
                dciphtext = dciphtext * Char(rotdciphnuml)
            else
                dciphtext = dciphtext * Char(dciphnuml)
            end
        else
            dciphtext = dciphtext * Char(numl)
        end
    end
    return dciphtext
end

text = "Zntvp Rapelcgvba"; key = 13
csrdcipher(text, key)
"Magic Encryption"
