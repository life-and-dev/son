## Legend

```mermaid
graph TD
    fact((Fact))
    reconcile([Reconcile\nContradiction])
    interpretation(Scriptural\nInterpretation)
    redefinition[Redefinition]
    assumption[/Assumption/]
    conclusion{Conclusion}
```

# Trinitarian Argument

No single argument proof the Trinity doctrine. This complex collection of arguments are required to support the Trinitarian view. As seen on the diagram below, the Trinitarian case hedge on certain unbiblical assumptions which are complicated to proof. For example the "divinity of Jesus", the "Dual Natures of Jesus", the "Personhood of the Holy Spirit", and the "Reconciliation of the Trinity with Monotheism".

```mermaid
graph TD
    subgraph Divinity of Jesus
        Word[Word\n=\nJesus] --> JesusGod{Jesus = God}
        Thomas(Thomas called Jesus\n'God') --> JesusGod
        Hebrews1(Hebrews 1:\nQuote YHWH as Jesus) --> JesusGod
        Revelation4(Rev 4:\nEveryone worship\nthe Lamb) --> JesusGod
        JesusEternal(Jesus is eternal) --> JesusGod
        ServeWorship((Sacrificial worship\nonly to God)) --> Worship[sacrifical\n=\nhomage]
        HonorWorship((Homage worship\nkings or God)) --> Worship
        Worship --> JesusGod
        JesusGod --> DualNature[Dual Natures\nof Jesus]
        DualNature -- human nature --> wordFlesh(John 1:\n'word become flesh'\n=\nGod incarnated) --> SonOfMan[Son of Man\n=\nhuman nature]
        SonOfMan --> JesusMan
        Jews((People\ntreated Jesus like\na human)) --> incompleteRev([incomplete\nrevelation]) --> JesusMan
        Temptations((Temptations)) --> humanPart([Only human part\nwas tempted]) --> JesusMan
        JesusMan((Jesus = Man)) --> JesusDied{Only\nJesus' body\ndied}
        JesusDied --> JesusRose{Jesus\nrose himself\nfrom dead}
        DualNature -- divine nature --> SonOfGod[Son of God\n=\n'God' the Son]
        SonOfGod --> JesusImmortal{Jesus\nis\nimmortal}
        JesusImmortal --> JesusLimits(Divine Jesus\nlimits himself)
        JesusLimits --> JesusDied
        SonOfGod --> Miracles(Miracles demo\nJesus' power)
        Miracles --> JesusRose
    end

    subgraph Persoonhood of Holy Spirit
        Interchangable(('Spirit' and 'God'\nused interchangably\nin Acts)) --> SpiritGod(Spirit = God)
        Provebs((Proverbs\nWisdom)) -- applied to HS --> SpiritPerson(Spirit = God)
        Personification((personification\npronouns)) -- applied\nliterally --> SpiritPerson
        SpiritGod --> SpiritPerson[/Spirit = distinct person/]
    end
    
    subgraph Creed: Reconcile Trinity with Monotheism
        SonOfGod -- see Jesus\n=\nsee Father --> JesusIsFather
        SonOfGod --> JesusSpirit(Paul mention\n'Spirit of Jesus')
        JesusIsFather{Jesus = Father} --> CoEqual
        FatherGod((Father = God = YHWH)) -- YHWH = LORD\nbut\nLord = Jesus --> JesusIsFather
                
        UsCreation(Pronoun 'us'\nused at Creation,\nbut 1 God) --> Trinity
        Baptism(Baptism\n'Formula') -- 3 names --> Trinity[/God = 3\nTrinity Persons/]
        3visitors((3 Lords\nvisited Abraham)) -- applies as\nTrinity members --> Trinity
        Mystery((Mystery)) -- excuse\ncontradictions--> Trinity
        JesusGod --> Trinity
        SpiritPerson --> Trinity
        Trinity --> Creed
        Creed[/Creed/] --> CoEqual[/Father = Jesus = Spirit/]
        
        JesusSpirit --> CoEqual
        CoEqual[/Father = Jesus = Spirit/] -- resolve\n3 = 1\ncontradiction --> 1God((1 God))
        Shema((Shema\n=\nonly 1 God)) -- 1 is not 1\n1 = unity --> 1God
        1God -- since Jesus = 1 God --> JesusRose
    end 
```

# Unitarian Argument

To proof the Unitarian case is biblical you only need the Shema, written by Moses in the Old Testament, quoted by Jesus himself in the New Testament, and affirmed by the apostles.

```mermaid
graph TD
    
    ShemaQuote((Jesus quote Shema:\nRabbi confirm it means 1)) -->|confirms| Shema
    Shema((Shema = Only 1 God)) -->|confirms| FatherGod(((God is YHWH\na.k.a.\n'God the Father')))
    Shema -->|proofs| JesusNotGod((Jesus is not God))
```

Still not convinced? Unlike the Trinitarian case that require all arguments to be true, the Unitarian case require any of the follow arguments to be true to disprove the Trinity:

```mermaid
graph TD
    
    subgraph Only 1 God
        Creator((1 Creator)) --> 1God
        Pronouns((Single\npronounce)) --> 1God
        
        Shema((Shema)) --> 1God
        NoOtherGod((God said\n'No Other God')) --> 1God
    end

    ShemaQuote((Jesus quote Shema:\nRabbi confirm it means 1)) --> Shema

    1God((Only 1 God)) --> FatherGod(((God is YHWH\na.k.a.\n'God the Father')))
    FatherGod --> Prophecies((Prophecies about\nIsraeli Messiah))
    Prophecies --> interaction
    Prophecies --> Distinct
    Prophecies --> Birth
    Prophecies --> Blood((Blood needed\nfor\nNew Covenant))

    subgraph Jesus is Distinct from God
        interaction((Interaction between\nGod and Jesus:\nGod send, authorize, exalt, etc.\nJesus serve, obey, pray, etc.)) --> Distinct
        Parables((Jesus own parables)) --> Distinct
        Declaration((God's public declarations\nseparate voice heard)) --> Distinct
        Stephen((Stephen's Vision)) --> Distinct
        Distinct((Jesus\nis distinct from\nGod))

        subgraph Jesus is Human
            FamilyLine((Jesus had tracable\nfamily line)) --> Birth
            Birth(("Jesus was born\nHad beginning\n(genesis)")) --> Increase((Jesus increase`\nor\n`grow`)) 
            Increase --> Jesus((Jesus = Human))
            Serve((Jesus\nserved & obeyed\nGod)) --> Jesus
            Jews((Disciples, apostles, enemies\ntreated Jesus like\na human)) --> Jesus
            Witness((Apostles witness\nhuman Messiah)) --> Jesus

            subgraph Jesus Died
                Limitations --> JesusDied
                Jesus --> JesusDied((Jesus died\nfor real))
                
                Blood --> JesusDied
                JesusDied --> JesusRose
                
            end
        end
    end

    Distinct --> Jesus

    
    Limitations((Jesus had real\nhuman limitations)) --> Jesus

    

    FatherGod --> JesusRose((Jesus risen by God))

    
    
```
