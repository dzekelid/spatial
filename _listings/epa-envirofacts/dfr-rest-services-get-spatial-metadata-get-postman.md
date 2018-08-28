{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) Detailed Facility Report Spatial Metadata Service",
    "_postman_id": "5d3da302-57f9-4286-9caa-9abfa29c82c6",
    "description": "Returns an object with the facility coordinate spatial metadata.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "3a790398-dc32-4644-a349-34f052dc8139",
      "name": "this-procedure-obtains-data-for-air-compliance-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Compliance in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f400afd1-5bfc-4055-994e-893e218ef25b"
        }
      ]
    },
    {
      "id": "5bd7510e-7fc1-4f33-8817-ad67be69cb38",
      "name": "this-procedure-obtains-data-for-air-quality-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_quality?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Quality in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "cef273ce-76ba-4304-afeb-64fad766340e"
        }
      ]
    },
    {
      "id": "66c245d6-a6a5-4350-83e6-59b496188fb2",
      "name": "this-procedure-obtains-data-for-the-compliance-monitoring-history-5-years-in-the-enforcement-and-com",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_history?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Compliance Monitoring History (5 years) in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "963f244e-a14b-4cb3-842d-59857769dcb0"
        }
      ]
    },
    {
      "id": "f5d70039-f3f0-4611-b365-21c19cc3b81f",
      "name": "this-procedure-obtains-data-for-compliance-summary-data-in-the-enforcement-and-compliance-section-of",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Compliance Summary Data in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "dbab9f1c-e9a7-4b71-a2e7-3b548d6086d7"
        }
      ]
    },
    {
      "id": "c87a64dd-b0d8-444b-a326-87c4d447d5b8",
      "name": "this-procedure-obtains-data-for-the-cwa-facilitylevel-status-section-located-in-the-three-year-compl",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_3yr_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:\n> \"In Viol\" = Facility is in violation\n> \"No Viol\" = No violation found\n> \"Unk\" = Unknown status\n> \"SNC/Cat 1\" = SNC/Category I violation found"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "4cc69c79-7f7d-46ec-afbb-52e32e57f199"
        }
      ]
    },
    {
      "id": "4e48c777-da6a-4c8d-b181-4a702d99f9aa",
      "name": "this-procedure-obtains-data-for-the-cwa-compliance-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_cs_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Compliance Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f138654e-7ea2-437e-b824-1972e46acc52"
        }
      ]
    },
    {
      "id": "dc5460ff-4e31-48bc-af2c-7bfa1cc1fe99",
      "name": "this-procedure-obtains-data-for-the-cwa-pollutant-discharge-section-located-in-the-three-year-compli",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_alr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Pollutant Discharge section located in the Three Year Compliance Status by Quarter portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "45cca051-8104-429b-9432-8f536d1ecc55"
        }
      ]
    },
    {
      "id": "fe5df800-9803-4d89-b34d-03d8bf1d8c15",
      "name": "this-procedure-obtains-data-for-the-cwa-effluent-compliance-section-on-the-dfr---",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Effluent Compliance section on the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a9d52452-f6a5-4cd1-aee4-dfc54cc11825"
        }
      ]
    },
    {
      "id": "5e647013-45b4-45ba-a814-7b04052241cb",
      "name": "this-procedure-obtains-data-for-the-cwa-permit-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_ps_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Permit Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "0a5e8e21-a328-45d6-9c27-64c07cdcecb4"
        }
      ]
    },
    {
      "id": "7f82c323-340d-4883-b4d5-882911a61b88",
      "name": "this-procedure-obtains-data-for-the-cwa-sncrnc-history-section-located-in-the-three-year-ompliance-s",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_rnc_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.\n> S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule\n> E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)\n> X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)\n> T = SNC/Category I - compliance schedule reporting violation\n> D = SNC/Category I - reporting violation - nonreceipt of DMR\n> N = RNC/Category II - reportable non-compliance\n> P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion\n> R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action\n> C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted \"m\".\n> Blank = Not considered in RNC/SNC\n> N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "63991b19-fc2d-405a-8b7c-c022ed8302e2"
        }
      ]
    },
    {
      "id": "0ebd1c4b-f14c-47bf-9291-1c8f38b705e2",
      "name": "this-procedure-obtains-data-for-the-cwa-single-event-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_se_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Single Event Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6756d5bb-24dc-4961-81bb-f9efd4114378"
        }
      ]
    },
    {
      "id": "ca0cc023-fdb8-4bd4-b3e2-b62d6446fc9c",
      "name": "returns-a-complex-object-with-demographics-from-the-2010-census-and-2010-american-community-survey-b",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_demographics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns a complex object with Demographics from the 2010 Census and 2010 American Community Survey based on a 3 mile radius around the facility spatial coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ddba03f5-53d2-4a7c-9e19-c06c7f94b619"
        }
      ]
    },
    {
      "id": "46f05540-52de-46f0-9e9e-3a748dfa01b9",
      "name": "this-procedure-is-the-overall-service-for-the-detailed-facility-report--it-returns-all-of-the-data-d",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_dfr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure is the overall service for the Detailed Facility Report. It returns all of the data displayed in the DFR web report by invoking individual procedures that each return a targeted portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "87e73f61-00f4-430a-933d-cc7f93c44da0"
        }
      ]
    },
    {
      "id": "9d6d3656-82b2-4386-a152-b8611c8a23e0",
      "name": "this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_enforcement_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Enforcement and Compliance Summary in the Facility Summary section of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "0606e509-2c5a-447a-bf8f-08657ed269e2"
        }
      ]
    },
    {
      "id": "9e37dded-c2d0-400a-8140-f373bdf9cf05",
      "name": "this-procedure-obtains-data-for-the-formal-enforcement-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "50dd9ba3-cd39-4850-bf70-d0f7949fae76"
        }
      ]
    },
    {
      "id": "837a6558-ae1f-4d01-a2c6-0558325a3462",
      "name": "this-procedure-obtains-data-for-the-integrated-compliance-information-system-formal-enforcement-acti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_icis_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Integrated Compliance Information System, Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "10addce2-f825-47c6-b65c-995bf8e3702d"
        }
      ]
    },
    {
      "id": "1db70257-915c-41a8-8c6a-6fb66801bcb5",
      "name": "this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_inspections?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Enforcement and Compliance Summary Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "0fb7c89b-210b-4161-a70f-33c3ad4b05bb"
        }
      ]
    },
    {
      "id": "21e064a9-0962-47de-961a-aad4f5e51bd4",
      "name": "returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_map?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns an object with the facility's latitude and longitude coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f97acce0-1010-458e-aa24-dc527602b5f3"
        }
      ]
    },
    {
      "id": "e5c125ba-8398-4ae3-bb64-772fcddbb944",
      "name": "this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_naics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Facility NAICS Codes section in Facility/System Characteristics of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d851dbe5-9acb-4227-9412-5a649383580e"
        }
      ]
    },
    {
      "id": "782e0769-b8e0-40c6-95c5-6e81dc87d544",
      "name": "this-procedure-obtains-data-for-the-permits-by-statute-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_nnnPermits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Permits by Statute section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "dc7cb429-b0d3-4650-a454-e71fb7fe14e7"
        }
      ]
    },
    {
      "id": "0124517d-a88f-4283-b970-70e6742d22a6",
      "name": "this-procedure-obtains-data-for-the-noticesinformal-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_notices?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Notices/Informal Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "4d231a3b-9510-4eff-8d13-dd03c7d4aaae"
        }
      ]
    },
    {
      "id": "c4892509-459a-4804-958b-f56cf5e867fb",
      "name": "this-procedure-obtains-data-for-the-following-sections-of-the-detailed-facility-report--facility-inf",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_permits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the following sections of the Detailed Facility Report.\n> Facility Information (FRS) in the Facility Summary.\n> Regulatory Interests in the Facility Summary.\n> Also Reports in the Facility Summary.\n> Facility/System Characteristics in Facility/System Characteristics.\n> Facility Contact Information in Facility/System Characteristics.\n> Facility SIC Codes in Facility/System Characteristics section.\n> Facility NAICS Codes in Facility/System Characteristics section."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "bf13dae4-bddb-4c52-aebf-38fa9dd6b3f1"
        }
      ]
    },
    {
      "id": "f5123332-5369-4c55-872c-daea4c5ad2fa",
      "name": "this-procedure-obtains-data-for-the-rcra-compliance-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_rcra_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the RCRA Compliance section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "45d3f00c-5460-436a-9f64-1ce1958d0f4b"
        }
      ]
    },
    {
      "id": "2f83d73b-4c69-4757-884c-e4f58553a217",
      "name": "this-procedure-obtains-data-for-the-sdwa-lead-and-copper-rule-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_lead_and_copper?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Lead and Copper Rule section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "8642b3ec-a155-4ee9-9c9a-2b2c8cf757d2"
        }
      ]
    },
    {
      "id": "6ded3d1f-1547-42b9-a615-0bea73aa427a",
      "name": "this-procedure-obtains-data-for-the-sdwa-sanitary-surveys-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_sanitary_surveys?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Sanitary Surveys section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d650540c-0b44-4bb2-bcd9-8254ab1137c0"
        }
      ]
    },
    {
      "id": "6795bed0-4d3f-4e01-b9d6-a3fd26b522a7",
      "name": "this-procedure-obtains-data-for-the-sdwa-sanitary-site-visits-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_site_visits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Sanitary Site Visits section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "880f6df6-6bfb-4054-96b8-48e03e6d1b64"
        }
      ]
    },
    {
      "id": "0451bac0-2139-4ced-8136-35766f8fc184",
      "name": "this-procedure-obtains-data-for-the-sdwa-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_violations?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "1da1d07f-21a0-44e5-b31d-20470ee441a4"
        }
      ]
    },
    {
      "id": "99b3d71f-7742-497d-b7d1-47c27a2d8dd8",
      "name": "this-procedure-obtains-data-for-the-sdwa-compliance-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwis_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA Compliance section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ee160d1c-8a96-4e42-9384-3068320793cc"
        }
      ]
    },
    {
      "id": "71c0eedb-ecdc-4ed8-814f-0045177881f8",
      "name": "this-procedure-obtains-data-for-the-facility-sic-codes-section-in-facilitysystem-characteristics-of-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sic_codes?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Facility SIC Codes section in Facility/System Characteristics of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ff1591ef-b2d2-4726-b4b5-afdcef3db6c8"
        }
      ]
    },
    {
      "id": "d069eba9-adea-4b4b-b011-3362b3f1b01c",
      "name": "returns-an-object-with-the-facility-coordinate-spatial-metadata-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_spatial_metadata?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns an object with the facility coordinate spatial metadata."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "86f085bb-d5e7-4a38-a977-4ee3852042b9"
        }
      ]
    }
  ]
}