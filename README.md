~~~~~~~~~~~~~~~~

//***FILE 027 IS FROM DAYCO PRODUCTS INC OF DAYTON OHIO AND         *   FILE 027
//*           CONTAINS A COPY OF THEIR DATE CHECK UTILITY.          *   FILE 027
//*                                                                 *   FILE 027
//*           THIS UTILITY WAS CREATED TO ALLOW PROGRAMMERS WHO     *   FILE 027
//*           BUILD SYSTEMS THAT REQUIRE DATE INPUT TO THE PARM     *   FILE 027
//*           OF A PROGRAM, TO ENSURE THAT IF THE DATE IS ENTERED   *   FILE 027
//*           WRONG THE OPERATOR DOES NOT GET AWAY WITH IT.         *   FILE 027
//*                                                                 *   FILE 027
//*           THIS FILE IS IN IEBUPDTE SYSIN FORMAT AND CONTAINS    *   FILE 027
//*           THE FOLLOWING MEMBERS.  SEE MEMBER $$DOC FOR          *   FILE 027
//*           ADDITIONAL INFORMATION                                *   FILE 027
//*                                                                 *   FILE 027
//*           $CLEAR    -    CLEAR FLAG MACRO.  USED WITH           *   FILE 027
//*                          $FLAG, $DFLAG AND $TEST MACROS.        *   FILE 027
//*                                                                 *   FILE 027
//*           $DFLAG    -    DEFINE FLAG BYTE MACRO.  USED WITH     *   FILE 027
//*                          $FLAG, $CLEAR AND $TEST MACROS.        *   FILE 027
//*                                                                 *   FILE 027
//*           $EPILOG   -    END AND EXIT A PROGRAM CSECT.          *   FILE 027
//*                          USED WITH $PROLOG MACRO.               *   FILE 027
//*                                                                 *   FILE 027
//*           $FLAG     -    SET A FLAG BIT MACRO.  USED WITH       *   FILE 027
//*                          $CLEAR, $DFLAG AND $TEST MACROS.       *   FILE 027
//*                                                                 *   FILE 027
//*           $HEAD     -    CREATE HEADER INFO BLOCKS IN           *   FILE 027
//*                          ASSEMBLY LISTINGS.                     *   FILE 027
//*                                                                 *   FILE 027
//*           $PROLOG   -    CREATE STANDARD ENTRY LINKAGE TO A     *   FILE 027
//*                          PROGRAM CSECT.  USED WITH $EPILOG      *   FILE 027
//*                          MACRO.                                 *   FILE 027
//*                                                                 *   FILE 027
//*           $REGS     -    INTERNAL MACRO USED BY $PROLOG TO      *   FILE 027
//*                          GENERATE REGISTER EQUATES.             *   FILE 027
//*                                                                 *   FILE 027
//*           $TEST     -    TEST A FLAG AND BRANCH ON              *   FILE 027
//*                          CONDITION MACRO.  USED WITH $FLAG,     *   FILE 027
//*                          $DFLAG AND $CLEAR MACROS.              *   FILE 027
//*                                                                 *   FILE 027
//*           #CONVDAT  -    CONVERT JULIAN DATE TO GREGORIAN       *   FILE 027
//*                          DATE MACRO.                            *   FILE 027
//*                                                                 *   FILE 027
//*           DATECHCK  -    DATE CHECK PROGRAM SOURCE.             *   FILE 027
//*                                                                 *   FILE 027
//*           DAYC ? ? ?-    THESE ARE ISPF TUTORIAL MENUS TO       *   FILE 027
//*                          EXPLAIN USAGE OF DATECHCK              *   FILE 027
//*                          UTILITY.                               *   FILE 027
//*                                                                 *   FILE 027
//*           THE MACROS EXCEPT THE $DFLAG, $TEST, $FLAG AND        *   FILE 027
//*           $CLEAR ARE FROM VARIOUS FILES IN THE UTILITIES TAPE.  *   FILE 027
//*           THE #CONVDAT MACRO WAS MODIFIED FOR REENTRANCY.       *   FILE 027
//*                                                                 *   FILE 027
~~~~~~~~~~~~~~~~

