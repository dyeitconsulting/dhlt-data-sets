DOE_TEST_DATA - EXPANDED TEST SET
=================================
Generated September 06, 2026

Case: John Michael Doe v. Jane Elizabeth Doe
Superior Court of Gwinnett County, Georgia, CAFN 26-A-01234-5
Client = Plaintiff (Husband). Defendant (Wife) served the discovery.
Married 06/14/2014. Separated 03/09/2025. Filed 02/03/2026. Two minor children.


WHAT IS IN THIS PACKAGE
-----------------------
01_Discovery_Served/
    Defendant's First Continuing Notice to Produce and Request for Production
    of Documents to Plaintiff  (.docx and .pdf)
        56 numbered requests: 50 substantive wide-ranging categories plus
        6 standard catch-alls (responsive-to-interrogatories, trial exhibits,
        attorney fee payments, credit report, notes and diaries, tangible
        evidence of the other party's conduct).

    Defendant's First Continuing Interrogatories to Plaintiff  (.docx and .pdf)
        30 numbered stems. Counting lettered subparts, the set totals
        EXACTLY 50 and is compliant with O.C.G.A. Sec. 9-11-33(a)(1).
        The preamble states the count, the way a careful drafter does.
        Numbering is shown as ranges (for example "3.-6.") wherever an
        interrogatory carries subparts, so the running count is visible.

    (The Requests for Admission already in the folder stay at 10 - untouched.)

02_Client_Uploads/
    1,000 raw production files, unorganized and unrenamed, the way they
    arrive. Every readable document has real content: line-item transactions,
    running balances, account numbers, statement periods, dates, and party
    names, so financial review and inventory tools have something to extract.

_ANSWER_KEY.xlsx / _ANSWER_KEY.csv
    One row per file. Tells you what each file actually is, which RPD
    category it answers, the party, the date, the key dollar figure, and
    which planted issue (if any) it carries. Three summary tabs.


FORMAT MIX (1000 files)
    .pdf   785
    .png   61
    .eml   59
    .xlsx  27
    .jpg   25
    .heic  16
    .csv   11
    .jpeg  6
    .docx  5
    .txt   3
    .qfx   2

Roughly 79% PDF, which is what a real production looks like, with enough
images, email, spreadsheets and native exports to exercise every path.


WHAT IS DELIBERATELY WRONG IN THE DATA
--------------------------------------
The corpus is built around one sworn Domestic Relations Financial Affidavit
that acts as the benchmark. The affidavit is wrong in specific, findable
ways, and the source documents prove it:

  * Four undisclosed accounts - Ally Bank ...5561 savings, a Coinbase
    account, a Robinhood brokerage, and a Schwab Roth IRA. Each is provable
    from transfers visible in the produced bank statements, from 1099s, and
    from the credit report.
  * One undisclosed debt - a Barclays card opened after separation.
  * A $60,000 HELOC advance three weeks before filing, with the proceeds
    landing in the Peachtree checking account and never traced.
  * Repeated teller cash withdrawals at or just under $9,000 in the months
    before filing.
  * Transfers to a third party after the date of separation, across Zelle,
    Venmo and Cash App, corroborated by a lease and text screenshots.
  * 2023 Schedule C income omitted from the return and picked up later on a
    Form 1040X, with the CPA email that forced it.
  * A missing run of statements (Truist ...8802, March through May 2025)
    right at the separation date.
  * Conflicting copies of four statement periods - same account, same month,
    different opening and closing balances.
  * An $18,400 watch on the AMEX and a boat with a bill of sale, neither on
    the personal property schedule.
  * Gig income (DoorDash, Turo) with 1099-Ks, reported nowhere.
  * A declined $184,000 job offer, relevant to earning capacity.
  * Separate property tracing problems - a gift letter, a Form 709, an
    estate accounting, and a personal injury settlement, all commingled.

Plus the ordinary mess: 44 exact duplicates with "- Copy" and "(1)" names,
8 PDFs holding three statement periods each, 14 blank scans, 7 image-only
scans with no text layer (including a handwritten note listing the hidden
accounts), 10 third-party documents that should not have been produced,
and 2 attorney-client emails that should have been withheld and logged.

342 of the 1,000 files carry at least one planted issue. The other 658 are
ordinary and correct, so precision is testable, not just recall.


FILENAMES
---------
Names are realistic client mess: scan0042.pdf, Doc17.pdf, IMG_2841.jpg,
untitled (3).pdf, MARCH STATEMENT.PDF, "june bank - Copy (2).pdf",
20250118_174535.pdf, and descriptive-but-inconsistent names. All are
Windows-safe. Nothing in the filename tells you the balance, so the
renamer has to open the file.


HOW TO INSTALL
--------------
Extract into:
  ...\+Discovery Tester\DOE_TEST_DATA\

02_Client_Uploads in the zip REPLACES the existing 105-file folder.
The existing "02_Client_Uploads - as is" and "- renamed" folders are not
touched; regenerate those from the new raw folder when you next test the
renamer.


DETERMINISTIC
-------------
Seeded at 20260906. Re-running the generator reproduces byte-identical
content, so a regression in a skill is distinguishable from a change in
the data.
